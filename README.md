# 🛍️ Product Classifier: Powering E-commerce with AI

Welcome to the Product Classifier repository! Dive into the world of e-commerce with our state-of-the-art Convolutional Neural Network (CNN) model. Ever wondered how e-commerce giants automatically categorize millions of products? Here's your chance to get a glimpse!

## 📊 Dataset: Behind the Scenes

Our treasure trove of data has been meticulously crawled from a bustling e-commerce platform. Each product name is like a unique fingerprint, telling its own story:

- `X_train.csv`, `y_train.csv`: The training ground! Product names meet their destined categories here.
- `X_valid.csv`, `y_valid.csv`: The tuning arena. Here, our model learns to refine its skills without getting too cocky.
- `X_test.csv`, `y_test.csv`: The ultimate test. This is where our model proves its mettle on fresh, unseen data.

## 🧠 Model: The Brain of the Operation

Our CNN model isn't just any model; it's a carefully crafted masterpiece:

- An **embedding layer** that weaves intricate patterns from input sequences.
- A **1D convolutional layer** with 32 sharp-eyed filters, each of size 8, ready to spot patterns.
- A **max-pooling layer** that knows when to focus and when to generalize.
- A **flatten layer** that simplifies complexities.
- Two **dense layers**, with the finale being a grand 37-neuron layer, each neuron representing a unique product category.

With the categorical cross-entropy as its guide and the Adam optimizer as its compass, our model embarks on its training journey. And to ensure it doesn't stray, we've given it an early stopping callback as its guardian.

## 🚀 Quick Start

1. 🍴 Fork or clone this repository.
2. 📘 Launch the `product classifier.ipynb` notebook in Jupyter.
3. 🚦 Follow the steps and watch the magic unfold!

## 🏆 Achievements

Hold your applause! Our CNN model dazzled with an accuracy of approximately **91.53%** on the test runway.

## 🤝 Join the Adventure!

Got ideas? Noticed a bug? Or just want to say hi? Feel free to fork, make your mark, and shoot us a pull request. Every contribution lights up our day!
