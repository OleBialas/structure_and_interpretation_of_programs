# Structure and Interpretation of Computer Programs

Exercises and notes from SICP using Jupyter notebooks with Racket.

## Setup

### Prerequisites

- VSCode with Jupyter extension
- Ubuntu/Debian (WSL works)

### Installation

1. **Install Racket**

   ```bash
   sudo apt install racket
   ```

2. **Install the iRacket Jupyter kernel**

   ```bash
   raco pkg install iracket
   raco iracket install
   ```

3. **Install the SICP language package**

   ```bash
   raco pkg install sicp
   ```

4. **Restart VSCode** and select "Racket" as the kernel for your notebook.

### Usage

In the first cell of each notebook, load the SICP package:

```racket
(require sicp)
```

Then write SICP-style Scheme code in subsequent cells:

```racket
(define (square x) (* x x))
(square 5)
```

## Resources

- [SICP Book (free online)](https://mitp-content-server.mit.edu/books/content/sectbyfn/books_pres_0/6515/sicp.zip/index.html)
- [SICP Racket package docs](https://docs.racket-lang.org/sicp-manual/)
