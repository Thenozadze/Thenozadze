<svg
  width="200"
  height="200"
  viewBox="0 0 200 200"
  xmlns="http://www.w3.org/2000/svg"
  version="1.1"
>
  <style>
    /* Define the animation */
    @keyframes moveAndColorChange {
      0% {
        fill: #ff6347; /* Start color: Tomato */
        transform: translate(0, 0); /* Start position: top-left */
      }
      50% {
        fill: #ffa500; /* Mid color: Orange */
        transform: translate(100px, 100px); /* Mid position: center */
      }
      100% {
        fill: #00ced1; /* End color: DarkTurquoise */
        transform: translate(200px, 0); /* End position: top-right */
      }
    }

    /* Apply the animation to the SVG element */
    rect {
      animation: moveAndColorChange 4s infinite;
    }
  </style>

  ![Animated SVG](thenozadze/thenozadze/Logo_Orgnl.svg)

  <rect x="0" y="0" width="50" height="50" rx="8" ry="8" />
</svg>
