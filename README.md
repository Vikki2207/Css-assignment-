# Css-assignment-
/* Define the animation */
@keyframes move {
  from {
    transform: translateX(0);
  }
  to {
    transform: translateX(100%);
  }
}

/* Apply the animation to the element */
.element {
  position: absolute;
  left: 0;
  top: 50%;
  transform: translate(-50%, -50%);
  animation: move 5s linear infinite;
}
