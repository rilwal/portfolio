---
title: Notris
slug: notris
layout: project
tags: project
categories: ['C++', 'Game']
thumbnail: /img/notris.png

project_type: Game Programming
credits: Programming - Jason Light
tools: C++ / SDL
duration: 2 Weeks

description: Notris is a Tetris-style falling block game made in C++ with the SDL library.
---



<figure class="figure mx-auto d-block" >
    <video class="figure-img img-fluid rounded center" playsinline autoplay="true" loop onclick="(e)=>{e}">
        <source src="/img/dt.webm" type="video/webm">
        <source src="/img/dt.mp4" type="video/mp4">
    </video>
    <figcaption class="figure-caption">Gameplay.</figcaption>
</figure>


## The Challenge
            
I decided to challenge myself to make a falling block game similar to Tetris® using only C++ and SDL. I chose C++ because it is the language most commonly used in the video games industry, because I am familiar with it,
and because I enjoy working with it. I chose SDL because I feel like the abstractions it provides are enough to avoid some of the fiddliness of writing cross-platform code, but still doesn't get in the way or do too much for you.
                        
My initial goal was simple: to create a functional Tetris style game in a weekend.
            

## The Plan

I'm a huge fan of Tetris, so I had a good idea of my requirements right from the start. I wanted more or less these features:        



* Basic Tetris functionality

    + 10x20 board
    + Movement of pieces from left to right
    + Rotation of pieces
    + Gravity to pull pieces down
    + <a href="https://harddrop.com/wiki/Drop#Soft_drop">Soft drop</a>
    + <a href="https://harddrop.com/wiki/Drop#Hard_drop">Hard drop</a>
* <a href="https://harddrop.com/wiki/SRS">SRS</a> style rotation
* <a href="https://harddrop.com/wiki/Random_Generator">Random bag</a> based piece randomization
* Hold Piece
* Ghost piece
* Scoring system
* Level system (difficulty increase over time)


    
## Initial implementation

    During the first weekend, I managed to implement most of the basic features.


<figure class="figure mx-auto d-block">
    <img  src="/img/notris-old.png" class="figure-img img-fluid rounded center " alt="">
    <figcaption class="figure-caption">The original version</figcaption>
</figure>

## Visual overhaul
Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae non nisi officiis maxime enim necessitatibus, dolores, amet id ipsum iusto voluptates vero, recusandae molestiae! Distinctio, nemo modi? Enim, fugiat explicabo.
