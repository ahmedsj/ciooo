<style>
#your-element-selector {
  background: transparent !important;
}
canvas {
  background: transparent !important;
}
</style>

<script src="three.r134.min.js"></script>
<script src="vanta.halo.min.js"></script>

<script>
VANTA.HALO({
  el: "#your-element-selector",
  mouseControls: true,
  touchControls: true,
  gyroControls: false,
  minHeight: 200.00,
  minWidth: 200.00,
  backgroundColor: 0x000000,
  backgroundAlpha: 0.0
})
</script>
