# NEXUS UNDERWORLD — GPU cloud workstation

## Target workstation
Ubuntu 22.04 or supported Windows desktop; 8 vCPU; 32 GB RAM; NVIDIA GPU with at least 16 GB VRAM; 200 GB SSD. Verify Vulkan, remote streaming and Unreal Engine 5.8 support with provider.

## Acceptance checklist
1. Verify GPU, driver and Vulkan support; run nvidia-smi and vulkaninfo --summary on Linux.
2. Install Unreal Engine 5.8 from Epic's official source.
3. Open and compile the starter C++ project.
4. Save the first 3D map as Content/Maps/L_PortoAurora_Blockout.umap.
5. Test third-person movement, collision, day/night and weather.
6. Record FPS, screenshots, editor logs and known defects.

## Security and cost
Use MFA, restricted remote access and billing alerts. Stop GPU instances after each session. Confirm persistent disk, network egress, licensing and storage charges. Never commit credentials.

## Provider shortlist
- Vagon: easy remote desktop; verify Linux and Vulkan availability.
- Google Cloud: documented Ubuntu GPU workstation with NVIDIA L4.
- AWS EC2: G5/G6 GPU machines; requires desktop-streaming configuration.

No machine has been purchased or provisioned yet.
