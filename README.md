# Word Loop vocabulary demo

A dependency-free vocabulary memorization demo for English learners. Swipe a word right when you know it, or left when you need another try. After marking a word as mastered, check its answer and use **I got it wrong** if you need to return it to the end of the queue. A word stays in the rotation until it is mastered.

## Run locally

From this folder, start a local server:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in a browser.

Keyboard controls: use the right arrow to mark a word as mastered and the left arrow to return it to the end of the list.
