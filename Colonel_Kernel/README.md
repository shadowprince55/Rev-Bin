### Colonel Kernel 

Just building a kernel. Yay!

----

<pre><code>sudo apt update 
sudo apt install nasm 
nasm -v 
sudo apt install qemu-system-x86 
qemu-system-x86_64</code></pre>

---

Once you write some assembly and christen her '.asm', check her execution in qemu using these commands. Assume that she is Ms boot.asm
<pre><code>nasm -f bin ./boot.asm -o ./boot.bin
ndisasm ./boot.bin
qemu-system-x86_64 -hda ./boot.bin
</code></pre>
