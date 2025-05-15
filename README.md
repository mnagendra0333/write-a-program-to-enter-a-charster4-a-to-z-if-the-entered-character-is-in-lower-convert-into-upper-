# write-a-program-to-enter-a-charster4-a-to-z-if-the-entered-character-is-in-lower-convert-into-upper-
ch= input("enter any character from a-z")
if ch>='A' and ch<'Z':
    ch=ch.lower()
    print("covertyed case of input char:",ch)
else:
    ch= ch.upper()
    print("covertyed case of input char:",ch)
