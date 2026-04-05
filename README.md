<h1>Soft Multi‑Material Magnetic Fibers and Textiles with Integrated Sensing</h1>
<h3>A Soft‑Robotics Platform with Embedded Perception and ML‑Driven Curvature Tracking</h3>

<h2>Overview</h2>
<p>
  This repository contains the published paper for our research on
  <strong>soft multi‑material magnetic fibers</strong> with <strong>integrated sensing and real‑time perception</strong>.
  The system combines:
</p>
<ul>
  <li><strong>Thermally drawn soft‑robotic fibers</strong></li>
  <li><strong>Piezoresistive CNT/CPE sensing layers</strong></li>
  <li><strong>Magnetic actuation</strong> using NdFeCoB elastomers</li>
  <li><strong>YOLOv8‑based pose estimation</strong> for curvature tracking</li>
  <li><strong>Programmable textile assemblies</strong> for rehabilitation and soft orthoses</li>
</ul>
<p>
  This work is presented in our scientific paper, which details the fabrication, sensing, actuation,
  and ML‑based perception pipeline.
</p>

<h2> Technical Highlights (Robotics • Computer Vision • Machine Learning)</h2>

<h3>1. Soft‑Robotic Fiber Fabrication</h3>
<p>
  We use <strong>thermal drawing</strong> to co‑draw thermoplastic elastomers, CNT/CPE nanocomposites,
  magnetic composites, and metallic conductors into a unified fiber architecture with an aspect ratio of 10<sup>5</sup>.
  This enables:
</p>
<ul>
  <li>Mechanically robust, stretchable fibers</li>
  <li>Integrated piezoresistive sensing</li>
  <li>Embedded magnetic actuation</li>
  <li>Scalable production for soft‑robotic systems</li>
</ul>

<h3>2. Embedded Piezoresistive Sensing</h3>
<p>
  CNT and CPE layers act as <strong>soft, stretchable electrodes</strong> capable of detecting:
</p>
<ul>
  <li>Bending</li>
  <li>Stretching</li>
  <li>Compression</li>
</ul>
<p>Measured responses include:</p>
<ul>
  <li>≈ 140% ΔR/R at 100% strain</li>
  <li>≈ 15% ΔR/R under compression during bending</li>
</ul>
<p>
  These sensors provide <strong>proprioceptive feedback</strong> for soft‑robotic control.
</p>

<h3>3. YOLOv8‑Based Curvature Tracking (Computer Vision + ML)</h3>
<p>
  A full perception pipeline was developed using <strong>YOLOv8 pose estimation</strong> to track fiber deformation
  in real time.
</p>
<p>Pipeline components:</p>
<ul>
  <li>Custom dataset with <strong>9‑keypoint annotations</strong></li>
  <li>Preprocessing (resizing, normalization, augmentation)</li>
  <li>Training YOLOv8n/m models with transfer learning</li>
  <li>Real‑time inference for curvature estimation</li>
  <li>Synchronization with electrical sensing data</li>
</ul>
<p>Performance:</p>
<ul>
  <li>mAP50 ≈ <strong>0.9</strong></li>
  <li>mAP50‑95 ≈ <strong>0.7</strong></li>
  <li>Precision/recall ≈ <strong>0.85</strong></li>
  <li>Real‑time tracking at ~30 FPS</li>
</ul>
<p>
  This transforms the fiber into an <strong>intelligent soft‑robotic element</strong> with embedded perception.
</p>

<h3>4. Magnetic Actuation &amp; Programmable Textiles</h3>
<p>
  Magnetorheological elastomers (MRE 35) embedded in the fibers enable:
</p>
<ul>
  <li>Programmable shape morphing</li>
  <li>Force generation</li>
  <li>Textile‑based actuation</li>
</ul>
<p>
  A 5 × 5 cm textile patch generates <strong>≈ 7 N of force</strong> under a 250 mT magnetic field.
</p>
<p>Applications include:</p>
<ul>
  <li>Soft orthoses</li>
  <li>Rehabilitation assistance</li>
  <li>Wearable robotics</li>
  <li>Adaptive medical textiles</li>
</ul>

<h2> Key Features</h2>
<ul>
  <li>Soft‑robotic fibers with integrated sensing</li>
  <li>YOLOv8‑based real‑time curvature tracking</li>
  <li>Magnetic actuation and programmable textiles</li>
  <li>High‑sensitivity piezoresistive feedback</li>
  <li>Applications in rehabilitation and soft orthoses</li>
  <li>Scalable thermal‑drawing manufacturing</li>
</ul>
</p>

<h2>📄 License</h2>
<p>
  Specify your license here (e.g., MIT, Apache 2.0, etc.).
</p>
