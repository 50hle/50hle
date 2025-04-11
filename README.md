## Hi there 👋

<!--
**50hle/50hle** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<!DOCTYPE html>
<html>
<head>
<title>Web AR Example</title>
<script
src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
<script src="https://cdn.jsdelivr.net/gh/AR-js-
org/AR.js/aframe/build/aframe-ar.js"></script>
</head>
body>
<a-scene embedded arjs="sourceType: webcam;">
<a-marker preset="hiro">
<a-box position="0 0.5 0" rotation="0 45 0"
color="#4CC3D9"></a-box>
</a-marker>
<a-entity camera></a-entity>
</a-scene>
</body>
</html>
