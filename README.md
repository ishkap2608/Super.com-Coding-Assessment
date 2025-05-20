# Project Title: Data Cleaning

This project is about learning how to build solutions that scale. What started as a simple script using Pandas turned into a deeper dive into scalable data processing with Dask. It’s a reflection of my mindset: start simple, but always be thinking ahead.

## Chapter 1: Getting Started with Pandas

I kicked things off with the tried-and-true **Pandas** library. It was the obvious choice — flexible, well-documented, and perfect for small to medium-sized datasets.

### What I did:

- Loaded and processed data using Pandas DataFrames.
- Cleaned and transformed strings using vectorized operations and Python string methods.
- Built a clean, readable script that was easy to test and iterate on.

This approach was quick to implement and worked well with the current dataset. But it got me thinking…

## Chapter 2: Thinking Bigger

Pandas worked great — **for now**. But I started asking:  
_“What happens if this data grows 10x, 100x?”_

That’s when I began looking into tools that could scale beyond memory limits and take advantage of multiple cores. I wasn’t facing performance issues yet, but I wanted to future-proof my approach and explore how real-world data engineers handle larger-scale challenges.

## Chapter 3: Using Dask — Built for Scale

That led me to **Dask**, a library built to work like Pandas but with some serious power under the hood:

- **It scales** — from your laptop to a cluster, handling data too big for RAM by working in smaller chunks.
- **It’s fast** — Dask runs tasks in parallel across CPU cores or machines, which really speeds things up for large jobs.
- **It’s smart** — instead of running code immediately, it builds a task graph and executes efficiently when needed.

### What changed in the code:

Switching to Dask meant a few adjustments in how I wrote things, but the API being so similar to Pandas made the transition smooth. The real difference was behind the scenes — better memory handling, smarter execution, and the ability to handle way bigger data.

### But wait — isn’t the dataset still small?

Yes, and that’s a fair point. With this current dataset, the benefits of Dask over Pandas aren't massive. But that’s not the point — the goal was to:

1. Show that I understand how to build **scalable** solutions.
2. Proactively choose tools that **prepare for growth**.
3. Demonstrate that I’ve done the **research** and can adapt to the kind of challenges a data engineering role (like the one at Super.com) might throw at me.

## Conclusion: Why This Matters

This project reflects how I approach engineering problems: start simple, but always think a few steps ahead. It’s not just about getting the job done — it’s about doing it in a way that holds up when things get bigger, messier, or more complex.

Going from Pandas to Dask was a valuable learning experience and a way to build skills I know I’ll need in real-world data roles. It's one thing to clean a CSV — it’s another to build a pipeline that’s ready for scale.
