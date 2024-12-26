# Go Map Initialization Panic

This repository demonstrates a common error in Go: panicking when accessing a nil map.  Go maps are not automatically initialized; attempting to access or modify a nil map will result in a runtime panic.

The `bug.go` file contains the problematic code. The `bugSolution.go` file shows the corrected code with proper map initialization.

This is a crucial point for Go developers to understand to avoid runtime crashes.