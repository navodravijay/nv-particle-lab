# NV. Particle Lab
A project by Navod Ravindu Jayaweera.

## GitHub upload
Extract this ZIP. Upload the dist folder and this README.md to your repository root. Do not upload the ZIP itself.

## Cloudflare Pages (Git integration)
Connect your GitHub repository.
Production branch: main
Framework preset: None
Build command: exit 0
Build output directory: dist
Root directory: leave default (repository root)

## Features
Five particle forms, local MediaPipe hand tracking, fullscreen, hide/show controls, reduced-motion support and quality controls.
Camera requires HTTPS or localhost. Enable camera only when ready. Frames are not recorded or uploaded by the application; code and model downloads use external CDNs.

## Dependencies and verification
Hand tracking uses @mediapipe/tasks-vision 0.10.21 and the Google MediaPipe Hand Landmarker model. These are third-party components, not authored by the project creator. The interface and application code were built with AI assistance.
Full dependency/model license review is not completed. Retain applicable upstream licenses and notices when redistributing those components.
JavaScript syntax checked. Real-device camera and fullscreen testing is still required.
