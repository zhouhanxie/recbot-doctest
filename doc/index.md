# RecBOT

## Overview

[🤖️ RecBOT](./) is a comprehensive toolkit designed for the **development**, **deployment**, and **interaction** of Conversational Recommender System research. [🤖️ RecBOT](./) leverages the best practices from the [PyTorch](pytorch.org) and [🤗 Huggingface](https://huggingface.co/) ecosystem to streamline the learning process, reducing the need for additional effort.

<div class="mt-10">
  <div class="w-full flex flex-col space-y-4 md:space-y-0 md:grid md:grid-cols-2 md:gap-y-4 md:gap-x-5">
    <a class="!no-underline border dark:border-gray-700 p-5 rounded-lg shadow hover:shadow-lg" href="./tutorial"
      ><div class="w-full text-center bg-gradient-to-br from-blue-400 to-blue-500 rounded-lg py-1.5 font-semibold mb-5 text-white text-lg leading-relaxed">Quick Start</div>
      <p class="text-gray-700">Learn the basics and become familiar with launching and interacting with a 🤖️ RecBOT model.</p>
    </a>
    <a class="!no-underline border dark:border-gray-700 p-5 rounded-lg shadow hover:shadow-lg" href="./zoo/overview"
      ><div class="w-full text-center bg-gradient-to-br from-green-400 to-green-500 rounded-lg py-1.5 font-semibold mb-5 text-white text-lg leading-relaxed">Data and Model Zoo</div>
      <p class="text-gray-700">High-level overview of the existing 🤖️ RecBOT datasets and 🤖️ RecBOT pre-trained models.</p>
    </a>
    <a class="!no-underline border dark:border-gray-700 p-5 rounded-lg shadow hover:shadow-lg" href="./development"
      ><div class="w-full text-center bg-gradient-to-br from-pink-400 to-pink-500 rounded-lg py-1.5 font-semibold mb-5 text-white text-lg leading-relaxed">Developer Guides</div>
      <p class="text-gray-700">Learn how to create new datasets, develop new models and share your creations with 🤖️ RecBOT.</p>
   </a>
    <a class="!no-underline border dark:border-gray-700 p-5 rounded-lg shadow hover:shadow-lg" href="./reference/overview"
      ><div class="w-full text-center bg-gradient-to-br from-yellow-400 to-yellow-500 rounded-lg py-1.5 font-semibold mb-5 text-white text-lg leading-relaxed">API Reference</div>
      <p class="text-gray-7 00">Technical descriptions of how 🤖️ RecBOT classes and methods work.</p>
    </a>
  </div>
</div>

## Installation



<Tip>
We test our 🤖️ RecBOT toolkit on Linux, and leave Windows / MacOS development in the future.
</Tip>

### 1. PyTorch installation:

```bash
pip install torch # require torch>=2.0
```

### 2. 🤗 Huggingface installation:

```bash
pip install transformers, datasets, evaluate
```

### 3. 🤖️ RecBOT installation:

```bash
pip install recbot
```

