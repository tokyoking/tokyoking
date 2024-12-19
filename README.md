## Hi there 👋



<p align='center'>
<img src="http://uploads.disquscdn.com/images/b92b3b9c5f8886cf358a0e700dab6054f37bbc5868900f17160aa41677cbc9fe.gif">
</p>

<p align='center'>
dumping my notes for future reference
</p>
<p align='center'>
<b>please let me know on discord (.tokyoking) if you spot a mistake or have a question</b>
</p>
<p align='center'>
  newbie pwner (╥_╥)
</p>

### Heap

[HEAP techniques](../../../../../tokyoking/ctf/tree/main/heap/)

**Glibc 2.35**

- [getting leaks via UAF to perform house of botcake attack into FSOP on stdout to leak a stack addr then ROP to fgets() stackframe](../../../../../tokyoking/ctf/tree/main/heap/otherbins/ImaginaryCTF23/mailman/README.md)

**Glibc 2.31**

- [fake chunk into overwriting got entries to get a leak](../../../../../tokyoking/ctf/tree/main/heap/tcache/BACKDOOR23/Konsolidator)

- [fastbin dup attack into free_hook overwrite](../../../../../tokyoking/ctf/tree/main/heap/otherbins/JUSTCTF22/pwn_notes/)


**Glibc 2.29**

- [house of force attack into overwriting malloc hook](../../../../../tokyoking/ctf/tree/main/heap/otherbins/SUNSHINECTF23/House_of_Sus)

### Format String

- [write ROP to saved rip of main](../../../../../tokyoking/ctf/tree/main/format_string/BACKDOOR23/Baby_formatter)

- [overwrite the key to pass a check](../../../../../tokyoking/ctf/tree/main/format_string/BlueHensCTF24/)

### Shellcode

- [calling mprotect() into self modifying shellcode](../../../../../tokyoking/ctf/tree/main/shellcode/HKCERTCTF24/shellcode_runner3/)

- [getting a leak from not cleared fs_base register into calling one_gaget](../../../../../tokyoking/ctf/tree/main/shellcode/HKCERTCTF24/shellcode_runner3(revenge)/)

### Buffer overflow

- [Brute-forcing a fork() process into leaking canary](../../../../../tokyoking/ctf/tree/main/buffer_overflow/UTCCTF24)
