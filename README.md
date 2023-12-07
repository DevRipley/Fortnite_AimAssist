# Kio - Fortnite Aim Assist
KioAssist is a neural network aim assist that uses real-time object detection accelerated with CUDA on Nvidia GPUs.

## About

KioAssist can be modified to work with a variety of FPS games; however, it is currently configured for Fortnite. Besides being general purpose, the main advantage of using KioAssist is that it does not meddle with the memory of other processes.

The basis of KioAssist's player detection is the architecture written in Executable Windows Program.

A demo video (outdated) can be found [here](https://discord.gg/8fZ8AXnKUj).

![thumbnail](https://user-images.githubusercontent.com/45726273/126563920-193ca8df-de70-4a91-81ec-d781ee961332.png)

## Installation

1. Get the guide and updates here [Discord](https://discord.gg/8fZ8AXnKUj)

## Issues
- The method of mouse movement ([SendInput](https://github.com/zeyad-mansour/lunar/blob/45e05373036f8bd072667313c155e55735cd7f57/lib/aimbot.py#L126)) is slow. For this reason, the crosshair often lags behind a moving detection. This problem can be lessened by increasing the [pixel_increment](https://github.com/zeyad-mansour/lunar/blob/45e05373036f8bd072667313c155e55735cd7f57/lib/aimbot.py#L56) (e.g. to 4) so fewer calls to that function are made.
- False positives can also happen under certain lighting conditions.

If you find this project interesting or helpful, please star the repository.

## License
This project is distributed under [GNU General Public License v3.0](https://github.com/zeyad-mansour/KioAssist/blob/main/LICENSE) license.
