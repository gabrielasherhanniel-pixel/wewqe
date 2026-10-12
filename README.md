# A Little Puzzle

A small, standalone jigsaw page. Visitors solve the puzzle to unlock its configured website URL.

To configure it, put your image beside `index.html`, then set `PUZZLE_IMAGE_URL` to its filename and `DESTINATION_URL` to your website address near the top of the script in `index.html`. For example, use `puzzle.jpg` and `https://yourwebsite.com`. Visitors only see the puzzle; once all twelve pieces are placed, the website link appears. Use **Shuffle** to start over.

The included illustration remains as a fallback when `PUZZLE_IMAGE_URL` is empty. The unlocked website opens in a new tab.

To try it with a local web server, run `python3 -m http.server 8000` from this directory and open `http://localhost:8000`.
