# Buffering.html
<html>
<head>
<style>
div {
  margin: 50px auto;
  height: 50px;
  width: 50px;
  border: 4px solid lightgrey;
  border-radius: 50%;
  border-right: 4px solid black;
  border-top: 4px solid black;
  animation-name: buffer;
  animation-duration: 1s;
  animation-delay: 0s;
  animation-timing-function: ease-in-out;
  animation-iteration-count: infinite;
}

@keyframes buffer {
  0% {
    transform: rotate(0deg);
  }
  25% {
    transform: rotate(90deg);
    
  }
  50% {
    transform: rotate(180deg);
  }
  100% {
    transform: rotate(360deg);
  }
}
</style>
</head>
<body>
<div></div>
</body>
</html>
