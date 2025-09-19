# 1) Personalized Video Generation for Mobile Devices
## Technology

Personalized Video Generation for Mobile Devices

## Description

This technology generates personalized short videos from a single input image while preserving the identities of subjects and simulating selected motion types and visual styles. This must efficiently target high-quality videos on mobile devices with limited memory resources

**Requirements:**
- Personalized Video Generation:
  - Preserving Identities: Maintain the subject ID from the input image
  - Configurable and Editable Video Generation: Allow users to select motion/style types
  - High-Res Video: Generate a video of less than five seconds in a resolution suitable for wallpaper use
- Efficient Video Generation for Mobile Devices:
  - Model Reusability: Compatibility with models across Galaxy AI is welcomed
  - Model Optimization for Edge-Devices
  - Privacy-Preserving Video Generation: No external data sharing
    
## Reason
**Societal Impact**: High-quality short video generation significantly influences social media and digital content creation
**Privacy Preservation**: On-Device processing ensures the original user data remains private
Cost Efficiency: In considering recent cloud-side video generation, this highly reduces
operational costs for company
- Utilization Plan
1. Wallpaper/ Screen-Saver AI
Enable users to create personalized videos for device backgrounds and screen-savers.
2. Stickers, GIFs, and Avatars
Make user to share animate photos for sharing on social media with chosen styles and
motions to replace normal text conversations.
---
# 2) Technology for Text, Key Value, and Structured Information Extraction
## Technology

Technology for Text, Key Value, and Structured Information Extraction

## Description

To develop and optimize a technology for text recognition, key value extraction, and structured information extraction designed for mobile environments.

## Reason

- Traditional OCR systems rely heavily on visual cues such as character shapes, word structures, and layout patterns. While they achieve reasonable accuracy, they struggle in challenging scenarios — low-quality images, complex backgrounds, distorted text, and uncommon fonts. Moreover, the lack of contextual understanding leads to misinterpretation of visually similar characters and poor generalization across different languages and styles.
- This approach addresses these challenges by combining visual features with semantic understanding. This enables context-aware recognition, helping to disambiguate similar characters, handle noisy or occluded text, and significantly improve multilingual recognition.
- Most importantly, Key Value Extraction empowers the technology to go beyond simple text recognition by automatically extracting essential information from documents such as forms, invoices, receipts, tables, and contracts. This unlocks smarter data utilization in mobile scenarios and lays the foundation for AI-powered automation and intelligent Screen-AI experiences.
- Additionally, the technology improves reading order accuracy, preserves table layouts through advanced table detection, and prioritizes key content for seamless copy & paste. It also enables Structured Text Understanding (e.g., tables and charts), efficient block segmentation for better overlay translation, and unlocks advanced camera and gallery AI applications.

---
# 3) Real-Time Hair Cinemagraph Generation
## Technology

Real-Time Hair Cinemagraph Generation

## Description

This research theme focuses on generating realistic hair-blowing animations from a single static image or cinemagraph by simulating the natural motion of hair in the wind. The objective is to create photorealistic and temporally consistent animations automatically, without the need for manual editing. The approach combines computer vision for structural analysis, generative adversarial or diffusion-based models for motion synthesis, and physics-inspired hair dynamics for realism. Core technical requirements include efficient deformation field estimation, temporal coherence across frames, and high-resolution output. The system must also be optimized for mobile devices, targeting latency of less than 50ms per frame and a model size under 120MB to ensure seamless real-time performance.

Example images: https://github.sec.samsung.net/q1-kim/website/wiki

Required Technologies:
- **Hair Structure Estimation**: Algorithms to identify and segment hair regions accurately from still images.
- **Motion Synthesis Models**: Generative AI or physics-inspired models to simulate natural wind-driven hair movement.
- **Temporal Consistency**: Frame stitching or deformation field techniques to ensure smooth and realistic animation across time.
- **High-Resolution Output**: Advanced upscaling and refinement methods to maintain image quality.
- **Optimization for Mobile**: Lightweight models and efficient inference pipelines, with targets of under 50ms latency per frame and model size under 120MB for real-time mobile use.

## Reason

- **Automation of Visual Effects**: With the growing dominance of short-form video and user-generated content, creators demand tools that add cinematic quality without specialized skills. Automated hair motion enhances realism and appeal.
- **Creative Applications**: From fashion photography to digital art, realistic hair animation provides new opportunities for storytelling and visual impact.
- **Mobile-First Demand**: Since most content is produced and consumed on mobile platforms, lightweight and efficient models are essential for widespread adoption.
- **Expansion into AR/VR**: In immersive environments like AR and the metaverse, lifelike hair dynamics are crucial for creating engaging and believable avatars.

**Utilization Plan:**
- **Product Integration**: Incorporate real-time hair cinemagraph effects into existing creative tools and mobile editing applications, enhancing user engagement and competitiveness.
- **New Service Development**: Launch dedicated apps or SDKs enabling users to transform static photos into dynamic cinemagraphs, opening new revenue streams.
- **Partnership Opportunities**: Collaborate with social media platforms, camera apps, and AR/VR companies to embed this capability directly into their ecosystems.
- **Future Expansion**: Extend the technology beyond hair to simulate other natural elements, such as clothing or environmental effects, broadening its creative impact.

---
# 4) Perspective distortion correction using generative AI
## Technology

Perspective distortion correction using generative AI

## Description

To correct perspective distortion in the photos in camera and / or gallery scenarios using image processing and generative AI.

## Reason

- There are two types of distortions in photography : lens distortion and perspective distortion. These days, lens distortion correction is commonly performed in smartphones, including Samsung’s Galaxy phones. However, perspective distortion correction is not common in smartphone applications.
- Perspective distortion is related to the distance between the subject and the camera. For selfies, a large amount of perspective distortion causes the nose to appear larger than the subject expects, and the ears to be occluded, resulting in unsatisfactory selfie distortion. Lens distortion correction cannot correct for perspective distortion.
- It is a trend that the field of views (FOVs) of selfie cameras are growing. One of the main benefits of larger FOV selfie cameras is that they enable easier group selfies. However, for solo selfies, a larger FOV can result in larger perspective distortion because the distance between the camera and the subject needs to decrease in order to make the facial region occupy a desired portion of the total FOV.
- Unlike lens distortion, perspective distortion require generative AI technology to correct for, especially because of the potentially occluded ears in the selfie scenarios. For selfies suffering from severe perspective distortion, ears need to be generated, generated image needs to be blended well with the background, and the eyes, nose and mouth need to be re-mapped to make the selfie look like as if it were taken from a more appropriate farther distance.
- Even though this technology requires generative AI, hallucination cannot be tolerated because it needs to be utilized in selfie scenarios. For future commercialization, processing time should be realistic (less than a few seconds) in the mobile platform.

---
