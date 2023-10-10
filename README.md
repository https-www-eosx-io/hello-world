# whatsapp-gpt<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🦾</font></font>
* You'll need to run WhatsApp from a phone number using the golang library I'm using.
* You'll run a dedicated browser in another window that's controlling ChatGPT.
* Two terminals: `go run main.go`, and `python server.py`. I am extremely doubtful they will work for you on the first run.
* You can also try `multichat.py` if you want to watch two ChatGPTs talk to each other.
* This marks the end of the readme file; it is a bit sparse; thankfully the code is too! Just tuck in if you can... and I will try to add more here later.

Взаимодействие с людьми 
<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">📟</font></font>
<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🧟</font></font>






// Игрушечная реализация кубического корня с использованием метода Ньютона.
func CubeRoot(x float64) float64 {
    z := x/3 // Произвольное начальное значение
    для я := 0; я <1е6; я++ {
        предыдущий := z
        z -= (z*z*zx) / (3*z*z)
        if VeryClose(z, prevz) {
            вернуть z
        }
    }
    // Миллион итераций не сошёлся; что-то не так.
    паника(fmt.Sprintf("CubeRoot(%g) не сошёлся", x))
}

