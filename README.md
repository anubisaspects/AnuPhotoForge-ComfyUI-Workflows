# AnuPhotoForge-ComfyUI-Workflows

ComfyUI workflows inspired by AnuPhotoForge vULTIMATE 5-node pipeline.

## Files
- workflows/AnuPhotoForge_vULTIMATE_FaceLock_BodySculptor_OutfitAlchemist.json
- prompts/AnuPhotoForge_Master_Prompt_Template.txt

## Required Custom Nodes
- ComfyUI_IPAdapter_plus
- ComfyUI_InstantID
- ComfyUI-Impact-Pack + Subpack
- comfyui_controlnet_aux

## Usage
1. Install nodes via Manager.
2. Load the JSON workflow.
3. Set LoadImage to your locked reference.
4. Replace [occupation] in the positive prompt.
5. For hijab: generate [A] intact and [B] removed variants.
6. Outputs 9:16, faces to camera, video-ready.

Zero-drift FaceLock + BodySculptor + OutfitAlchemist + PhotorealOutput.