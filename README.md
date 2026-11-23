# Kai Voxel Room

A small shared 3D voxel room with peer-to-peer position sync and camera/microphone chat.

## Run

Open the GitHub Pages site or `for-kai.html` in a modern browser. The page uses PeerJS and Three.js from public CDNs, so the first load requires internet access.

## Join a friend

1. Both people open the same HTTPS site.
2. The first person enters a room name and joins. They become the host.
3. The second person enters the exact same room name and joins.
4. Allow camera and microphone access.

## Controls

- W/A/S/D or arrow keys — move the green block.
- The other person's block appears in pink when connected.

## Limitations

This is a small two-person demo, not a full multiplayer server. PeerJS supplies signaling and public STUN servers help establish WebRTC. Some networks require a TURN relay, and camera/microphone access requires HTTPS. Do not add private TURN credentials to this public repository.
