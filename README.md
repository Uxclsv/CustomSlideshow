# CustomSlideshow

![Build Status](link-to-build-status-badge)
![License](link-to-license-badge)

## Introduction

Welcome to `CustomSlideshow`, an Android library designed to provide a customizable slideshow experience for your app. Whether you're showcasing images, tutorials, or promotional content, this library offers flexibility and ease of use to enhance your user interface.

## Features

- **Customizable Transitions**: Fade, slide, zoom, and more for smooth slide changes.
- **Auto-play with Customizable Timing**: Control how long each slide is displayed before transitioning.
- **Manual Navigation**: Swipe or button controls for user interaction.
- **Indicator Support**: Dots or numbers to indicate the current slide position.
- **Image Loading**: Compatible with various image loading libraries like Glide or Picasso.
- **Content Types**: Supports images, text, or mixed content slides.
- **Easy Integration**: Simple setup via Gradle.

## Installation

To integrate `CustomSlideshow` into your project, add JitPack to your root `build.gradle`:

```gradle
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
