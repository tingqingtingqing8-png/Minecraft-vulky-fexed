# Minecraft-vulky-fexed
fexed   RenderPearl batching: Submitting the init and main command buffers together (c=2) causes VK_ERROR_DEVICE_LOST (-4) on ARM Mali GPUs (tested on Mali-G610). I solved this by splitting the submission and using a strict vkQueueWaitIdle sync
