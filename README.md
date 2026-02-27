# FastViDAR Project Homepage

This repository contains the source code for the [FastViDAR](https://zhao-hangtian.github.io/FastViDAR/) project website.

## About FastViDAR

**FastViDAR: Real-Time Omnidirectional Depth Estimation via Alternative Hierarchical Attention**

FastViDAR is a novel framework that takes four fisheye camera inputs and produces a full 360° depth map along with per-camera depth, fusion depth, and confidence estimates.

### Key Features

- **Alternative Hierarchical Attention (AHA)**: Efficiently fuses features across views through separate intra-frame and inter-frame windowed self-attention
- **ERP Fusion**: Projects multi-view depth estimates to a shared equirectangular coordinate system
- **Real-Time Performance**: Achieves up to 20 FPS on NVIDIA Orin NX embedded hardware

### Publication

This work has been accepted to **ICRA 2026** (IEEE International Conference on Robotics and Automation).

## Project Structure

```
.
├── index.html          # Main webpage
├── assets/
│   ├── css/            # Stylesheets
│   ├── js/             # JavaScript files
│   ├── videos/         # Demo videos
│   └── fonts/          # Font Awesome fonts
├── pdfs/               # Paper figures (PDF/PNG)
├── plys/               # Point cloud files for visualization
└── README.md
```

## Links

- **Website**: [https://zhao-hangtian.github.io/FastViDAR/](https://zhao-hangtian.github.io/FastViDAR/)
- **Code Repository**: [https://github.com/Zhao-hangtian/FastViDAR](https://github.com/Zhao-hangtian/FastViDAR)

## License

This website is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

Template inspired by [nerfies.github.io](https://github.com/nerfies/nerfies.github.io).
