# ComfyUI-Cloneworks
A growing collection of **custom nodes for ComfyUI**
built for modular workflows, ControlNet chaining and LoRA injection.

## Features  
- **ControlNet Sequencer** – stack multiple ControlNets (Pose, Canny, Depth, etc.) in sequence with adjustable strengths & ranges.  
- **Staged Refinement Support** – designed to integrate cleanly with 2-sampler workflows (structure → style).  
- **LoRA Injection Ready** – flexible placement of LoRA loaders before and after sequencing.  
- **Batch-Friendly** – works with ImpactPack / batch splitters for multi-image output.  
- **Expandable Toolkit** – future nodes for ApplyCN, style mixing, batch utilities, and more.  

## Installation

Clone this repo into your ComfyUI `custom_nodes` folder:

```bash
cd ComfyUI/custom_nodes
git clone https://github.com/dreambundler/ComfyUI-Cloneworks
