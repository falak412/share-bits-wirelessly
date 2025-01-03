# share bits wirelessly


![ss](/asset/Screenshot_2024-05-28_21-33-01.jpg)
## Try this💡
### Here is my simple solution for sharing really small files. 

Share small files from an offline source using only a QR code!

## Why?

Imagine: You want to share a file with a friend nearby. You want to share from a source that does not have internet access - you just want to beam the file directly to your friend. This system lets you _embed_ your file into a QR code that loads as an actual file download on your friend's device. Try it out here if you're feeling brave! The image that is downloaded by scanning this QR code **is not hosted on any server, it only lives _inside_ the QR code**.

![QR code with file embedded](/asset/thumb14.jpg)

## Usage

To generate one of these QR codes, you can either:
1. use the [web app](https://amanraox.github.io/share-bits-wirelessly/) (this can be saved to your computer to run offline).
2. use the included [python script](./generate_qr.py).
   1. Install the dependencies using `pip install -r requirements.txt`
   2. Run using `python3 generate_pr.py input_file.txt`. The QR code png will be generated with the same filename (+ `.png`) by default, or you can explicitly pass in an alternate output filename as a second argument.


  # CONTRIBUTING 

We welcome contributions to SHare Bits Wirelessly! To contribute:

1. Fork and Star the repository 🍴⭐
2. Create a new branch (`git checkout -b feature/your-feature`) 🌱
3. Make your changes ✨
4. Commit and push your changes 🚀
5. Create a pull request 🔄

## Contributors

A heartfelt thank you to the following individuals for their valuable contributions to this project. Your support and dedication are greatly appreciated:

<a href="https://github.com/amanraox/share-bits-wirelessly/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=amanraox/share-bits-wirelessly" />
</a>

<br>
