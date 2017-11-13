# Multitudes, an IPython notebook series on what's inside our files

> Do I contradict myself?
> Very well then I contradict myself,
> (I am large, I contain multitudes.)
*Walt Whitman, Songs of Myself*

I told a colleague I was curious about "perceptual image hashing," and we got to talking about image formats and how perceptual hashes aren't much different from a rather lossy compression, unlike the cryptographic hashes I was more aware of. This brought us to JPEG 2000 and how it makes it very clear how the format uses Discrete Cosine Transformations to encode images.

It lead me to realize that I only have a small familiarity with what goes inside a file. I get that there's structs in programs, that make bytes, that go into a file, but that's all rather arbitrary. What are the decisions for packing data in a way that other programs and machines understand? Ideally, in a way that's concise and not too intense to process or implement. Naturally, different formats optimize for different concerns. An uncompressed bitmap image is easier to decode than a JPEG, but certainly takes up more disk space and bandwidth.

Ideas for formats to look at:
1. Image formats:
    * BMP
    * GIF
    * JPEG
    * PNG
2. Lossless Compression schemes:
    * GZIP
    * Others? I need to research
3. Audio, Lossy and Lossless:
    * WAV
    * FLAC
    * OGG
    * MP3
4. Video and media containers
    * MPEG
    * AVI
    * MKV
    * Subtitle encoding
5. Documents
    * PDF
    * DOCX
    * PPT
    * XLS
    * Open/Libre Office
