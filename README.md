text = “””La 40 de ani, starul portughez a înscris din nou pentru Portugalia și a doborât un record impresionant, devenind cel mai bun marcator din istoria preliminariilor pentru Cupa Mondială!”””

m = len(text)//2

p1, p2 = text[:m].upper().strip(), text[m:][::-1].capitalize()

for s in [“.”, “,”, “!”, “?”]: p2 = p2.replace(s, “”)

rezultat = p1 + “ “ + p2

print(rezultat)
