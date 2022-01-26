# calculator.go

package main

import "fmt"

func main() {
	fmt.Println("selamat datang di calculator sederhana")

	var a int
	fmt.Println("1. perjumlahan")
	fmt.Println("2. pengurangan")
	fmt.Println("3. perkalian")
	fmt.Println("4. pembagian")
	fmt.Println("5. exit")
	fmt.Println("menu penjumlahan: ")
	fmt.Scanln(&a)
	switch a {
	case 1: 
		fmt.Println("_ _ _ _ _ _ _ _ _ _ _ _ _ _ _")
		fmt.Println("menu perjumlahan")
		var b int
		var c int
		fmt.Println("1: ")
		fmt.Scanln(&b)
		fmt.Println("2: ")
		fmt.Scanln(&c)
		var jumlah int = 1 + 2
		fmt.Println("hasil jumlah: ")
		fmt.Println(jumlah)

	}
