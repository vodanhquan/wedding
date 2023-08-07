function createHearts() {
  for (let i = 0; i < 10; i++) {
    const heart_bg = document.createElement("div");
    heart_bg.className = "heart_bg";
    document.body.appendChild(heart_bg);
  }
}
createHearts();
