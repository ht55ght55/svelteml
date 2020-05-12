# SvelteML <small>0.0.4</small>

Documentation: https://john--kane.github.io/svelteml/#/


![svelteml](https://github.com/john--kane/svelteml/blob/master/docs/_media/svelteml.png?raw=true)

## Overview 🤖 📖

The purpose of SvelteML is to offer simple Components that can make ML more accessible. It leverages TensorflowJS to offer Svelte apps ML features out-of-the-box. It relies heavily on Svelte's reactivity feature and event hooks can be used to extend out the ML flow. e.g. on:poses in the Pose Estimator will give you the raw poses directfrom TensorflowJS.

## Quick Start

    npm install svelteml --save

## Overview

> All Components try to be reactive so although it feels very declarative, it is also reacting to your input.
> Add an issue in Github if you need a specific behaviour or if there is a bug or would like to recommend something. You know the drill.

## What's next

### Classification / Segmentation

- [x] Image Classification
- [x] Body Segmentation
- [x] Basic Multi-Pose Estimation
- [x] Object Detection
- [x] Face Mesh
- [x] Hand Pose Detection

### Text-based inference

- [x] Sentence Encoding
- [x] Text Toxicity

### Image Effects

- [x] Blur Body Parts
- [x] Bokeh Effect

### Audio Effects

- [ ] Speech Command Recognition
