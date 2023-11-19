* Real mode allows access to only 16 bits at a time, super unsafe
* Segmentation Memory Model:
    * Memory is accessed by a segment and an offset
    * Programs loaded into different areas of memory can run without any problem
    * multiple segments are available through the use of segment registers
    * 8086 Segment registers: code, stack, data, extra
    * absolute offset/address of data = [(segment_register x 16) + data] => allows us to address 1 MB in RAM, in real mode
    * stacks grow downwards => pushing decrements stack
