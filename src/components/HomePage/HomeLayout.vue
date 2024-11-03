<template>
    <div class="flex flex-col min-h-screen bg-white">
      <!-- Main Content -->
      <main class="flex-grow">
        <!-- Hero Section -->
        <section class="hero-section relative flex flex-col w-full text-base font-bold text-white min-h-[738px] max-md:max-w-full">
          <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/e5bfae96974161f04c8b5ad03c87928ad2a5c634be38a70776d9aa2f815145ae?placeholderIfAbsent=true&apiKey=b642bcfadf164c35aebff8fb97b04ffb" alt="Hero background image showing a workspace" class="object-cover absolute inset-0 size-full" />
          <div class="relative flex flex-col items-start px-20 py-40 w-full max-md:px-5 max-md:py-24 max-md:max-w-full">
            <span class="font-semibold leading-none uppercase tracking-[3px]">
              <span class="font-medium">Posted on</span>
              <span class="font-black">startup</span>
            </span>
            <h1 class="mt-8 text-6xl tracking-tighter leading-[64px] max-md:max-w-full max-md:text-4xl max-md:leading-[51px]">
              {{ blogPost.title }}
            </h1>
            <p class="mt-9 leading-loose text-blue-600">
              By <a href="#" class="text-blue-600 hover:underline">{{ blogPost.author }}</a> | {{ blogPost.date }}
            </p>
            <p class="mt-7 leading-7 max-md:max-w-full">
              {{ blogPost.excerpt }}
            </p>
            <button class="gap-3 px-12 py-4 mt-16 -mb-10 text-lg leading-none bg-blue-600 hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-offset-2 max-md:px-5 max-md:mt-10 max-md:mb-2.5" aria-label="Read More">
              Read More >
            </button>
          </div>
        </section>
  
        <!-- Featured Posts Section -->
        <section class="featured-posts px-20 mt-32 w-full max-md:px-5 max-md:mt-10 max-md:max-w-full">
          <h2>Featured Posts</h2>
          <!-- Map through the featured posts data if needed -->
        </section>
  
        <!-- Categories Section -->
        <section class="categories px-20 mt-16 w-full max-md:px-5 max-md:mt-10 max-md:max-w-full">
          <h2>Categories</h2>
          <!-- Map through categories if needed -->
        </section>
  
        <!-- Newsletter Section -->
        <section class="newsletter bg-orange-50 px-16 py-20 mt-28 w-full max-md:px-5 max-md:mt-10 max-md:max-w-full">
          <form class="flex flex-wrap gap-5 justify-between w-full max-w-[1057px] max-md:max-w-full">
            <label for="newsletter-email" class="sr-only">Enter your email</label>
            <input 
              type="email" 
              id="newsletter-email"
              class="grow px-6 py-6 text-base leading-loose border border-solid border-neutral-600 text-zinc-500 w-fit max-md:px-5"
              placeholder="Enter Your Email"
              required
            />
            <button 
              type="submit"
              class="gap-3 px-12 py-4 text-lg font-bold leading-none text-white whitespace-nowrap bg-blue-600 hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-offset-2 max-md:px-5"
            >
              Subscribe
            </button>
          </form>
        </section>
      </main>
    </div>
  </template>
  
  <script lang="ts">
  import { defineComponent } from 'vue'
  
  // Define interfaces for BlogPost and Author
  interface BlogPost {
    title: string
    author: string
    date: string
    excerpt: string
    image: string
  }
  
  export default defineComponent({
    name: 'BlogLayout',
    data() {
      return {
        // Example data for blog post
        blogPost: {
          title: 'Step-by-step guide to choosing great font pairs',
          author: 'James West',
          date: 'May 23, 2022',
          excerpt: 'Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur...',
          image: 'https://example.com/image.jpg'
        } as BlogPost
      }
    }
  })
  </script>
  
  <style scoped>
  .visually-hidden {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    white-space: nowrap;
    border: 0;
  }
  </style>
  