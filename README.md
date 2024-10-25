# AquaSense
A desktop application to predict whether a sample of water is safe to drink or not. Written in Qt 6.


### Application Screenshots
| Screen | Preview |
|--------|---------|
| Screen 1 | ![Screen 1](https://i.postimg.cc/7YBzcLmn/1.png) |
| Screen 2 | ![Screen 2](https://i.postimg.cc/1tZV6V3s/2.png) |
| Screen 3 | ![Screen 3](https://i.postimg.cc/5tzF6S1s/3.png) |
| Screen 4 | ![Screen 4](https://i.postimg.cc/YCZWrsc4/4.png) |
| Screen 5 | ![Screen 5](https://i.postimg.cc/NM79xGKT/5.jpg) |
| Screen 6 | ![Screen 6](https://i.postimg.cc/T1dyN8bs/6.jpg) |
| Screen 7 | ![Screen 7](https://i.postimg.cc/mr9zngFh/aq.jpg) |

## Demo

[![AquaSense Demo](https://i.postimg.cc/YC50wxtx/Aqua-Sense-KU9s0m-WYoz.gif)](https://postimg.cc/jDhtHPwW)

## Project Overview

AquaSense allows users to input various parameters, sends this data to a cloud-based API, and receives predictions in return. This seamless backend communication made use of Azure Functions, but **you'll need your own logic and code for the API** (mine isn’t included in this repository).

The app is currently configured with placeholders for endpoints, so it’s ready for you to integrate with your API of choice. 

**Disclaimer:** I didn't track this project when developing it, and I deployed it 1 year later. I don't exactly remember what I wanted to change, and what the pitfalls were.

## Features
- **Input-to-Prediction Pipeline**: Users enter data, which is processed and sent to a cloud API.
- **Qt GUI**: A simple and intuitive interface for entering data and viewing results.
- **Customizable Backend**: Although initially designed for Azure Functions, you can modify the API URLs and parameters for any backend solution you choose.

## Backend Configuration

I used Azure Functions as the backend, but you’re free to adapt this to any backend service. Replace the placeholder API URL and key in the code with your own endpoint. 

**Disclaimer**: I was too lazy to add environment variables while coding this project, so you’ll find placeholders where the endpoint URLs and API keys should go. I’m aware that using environment variables is a better practice!

## Notes

- **Environment Variables**: While I didn’t use them back then (college project deadlines, you know?), I encourage you to implement them for sensitive information.
