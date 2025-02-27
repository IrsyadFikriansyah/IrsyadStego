# IrsyadStego: An Open-Source Steganographic Tool for Secure Data Hiding

## Introduction

**IrsyadStego** is a lossless steganographic software that utilizes the **Difference Expansion** algorithm to securely embed secret data within digital images. By leveraging a **pixel differencing paradigm**, the software optimally balances **payload capacity** and **stego image quality**. A custom **neighboring pixel difference range (-5 to 5)** is applied to improve embedding efficiency while preserving visual integrity.

This implementation includes **eight test images** and **eleven payload files**, with payload sizes ranging from **1 KB to 100 KB**, allowing for comprehensive evaluation of the method’s effectiveness.

## Features

- **Lossless steganography** ensuring full reversibility.
- **Customizable embedding parameters** for optimal balance between payload and image quality.
- **Simple and intuitive interface** for embedding and extraction.
- **Open-source implementation** in Python using Jupyter Notebook.

## Installation

To run **IrsyadStego**, ensure you have the following dependencies installed:

```bash
pip install numpy opencv-python matplotlib scikit-image