# 3D Image Generation from 2D Images and Videos

## Overview

Holosnap focuses on transforming 2D images and videos into 3D file formats such as `.obj`, `.glb`, and `.fbx`. Our technology combines deep learning and generative AI to create 3D representations from 2D data. The process includes generating point clouds, mesh construction, and feature extraction to achieve high-quality 3D outputs.

### Objectives

- Create 3D images from 2D images or videos.
- Generate detailed 3D file formats for post-processing by our manual 3D team.
- Enhance the depth and detail of 3D models using AI to fill in missing parts of objects.

### Current Status

- Point cloud generation from single images using a combination of original 2D and Generative AI techniques.
- Object segmentation and depth estimation from videos for 3D reconstruction.
- Ongoing development on feature extraction and object matching to improve model accuracy.

## Sample Output

See a demonstration of our process and output [here](demo/hhh/test.mp4).

## Processing Time

- The generation of 3D images from 2D input ranges between 2 to 9 minutes, depending on the number of images used.

## Accuracy

- The accuracy of our 3D models improves with the number of images processed. More images provide a more detailed point cloud, resulting in a more accurate 3D model.

## Roadmap

- Continue refining our AI algorithms and processing techniques.
- Expected product readiness for enterprise use within the next few months.

## Technologies

- **Deep Learning & Generative AI:** Leveraging the latest advancements in AI to enhance 3D model creation.
- **PyTorch:** Our primary framework for developing and training AI models.

## Research and Development

- **Research:** We actively follow the latest research from conferences like ICCV and ICLR.
- **Development:** All algorithms are developed from scratch, aimed to meet the specific needs of 3D reconstruction.

## Publication

- While we currently focus on product development and enterprise applications, we plan to publish our findings and contribute to the community post-launch.

## Getting Started

To clone and run this project locally, use the following commands:

```bash
git clone https://github.com/your-organization/your-project.git
cd your-project
# Follow local setup instructions
```

## Contributing

Interested in contributing? We welcome contributions from the community. Please read our [contributing guide](CONTRIBUTING.md) for more information on making submissions.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

For further inquiries, please contact us through [Github Issues](https://github.com/your-organization/your-project/issues) or our organization's contact form.
