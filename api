package api

import (
    "fmt"
    "net/http"
)

func Hola(w http.ResponseWriter, r *http.Request) {
    w.Header().Set("Content-Type", "text/plain")
    fmt.Fprintf(w, "hola mundo")
}
