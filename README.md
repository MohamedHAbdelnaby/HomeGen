# HomeGen

## Inspiration
When building a custom home, clients expect perfection in every detail. However, translating architectural plans into a reality that matches their expectations can be a challenge. Often, clients don’t fully grasp the spatial layout from blueprints alone. Misunderstandings about room sizes, window placements, or overall flow can lead to costly last-minute changes once construction begins. Even a minor adjustment after concrete is poured can cause significant delays, escalating costs, and frustration for both the client and the developer.

We wanted to solve this problem by creating a tool that bridges the gap between client expectations and the final build. Imagine being able to walk a client through a 1-to-1 scale model of their future home, right on their property, before any construction starts. With our solution, clients can visualize their home in its actual setting, ensuring complete confidence that their vision matches the reality.

## What It Does
Our software transforms architectural floor plans into a true-to-scale, immersive 3D experience. From the plans you already have, it automatically generates a fully detailed 3D asset, allowing clients to virtually walk through every room and hallway of their future home. This ensures that clients can experience the layout, dimensions, and design choices as if they were physically present inside the finished structure.

This immersive walkthrough gives clients the chance to explore, critique, and approve every aspect of their home before construction begins. The result? Fewer surprises, no costly change orders, and faster project timelines. Plus, our advanced texturing capabilities align with both developer and client visions, ensuring interior and exterior finishes meet everyone’s expectations from the start. It's a powerful tool for clear communication and precision planning.

## How We Built It
To bring our vision to life, we started by leveraging ShapesXR to prototype our 3D visualization tool, focusing on creating an intuitive and immersive user experience. The technical constraints of other platforms led us to choose ShapesXR for its flexibility and fast prototyping capabilities.

We also integrated AWS services to power our speech-to-text interface, allowing for seamless user commands and real-time adjustments. Speech accompanies a UI interface that draws inspiration from an architects' drawing desk. This approach streamlined the workflow, enabling developers and clients to explore design modifications on the fly. Our goal was to build a solution that’s both easy to adopt and impactful in reducing costly project iterations.

## Challenges We Ran Into
Initially, we envisioned using AI to convert 2D floor plans directly into detailed 3D models. However, existing text-to-3D mesh generation tools fell short, lacking the precision and fidelity required for architectural details. We faced challenges in maintaining the accuracy of the original plans while ensuring the 3D assets felt realistic and true to life.

## What's Next for HomeGen
The next step for HomeGen is to elevate the realism of our visualizations by porting our models to Unreal Engine. This transition will unlock lifelike rendering capabilities, providing clients with a hyper-realistic, fully immersive experience. Imagine a client standing on their future property, walking through a virtual replica of their home with photorealistic textures, lighting, and environmental effects.

We also aim to expand our feature set with more customization options, allowing clients to experiment with different materials, finishes, and layouts in real-time. As we integrate advanced rendering and interactive elements, our goal is to become the go-to solution for developers looking to streamline client approvals, reduce construction revisions, and deliver dream homes with unmatched precision.
