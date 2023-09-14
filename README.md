# Image Data Encoder & Decoder

This project allows you to encode and decode data into and from images. This can be a fun way to hide secret messages in images or provide a visual representation of your data!

## Installation

1. Ensure you have Go installed on your system. If not, [download and install it](https://golang.org/doc/install).
2. Clone this repository:
   ```
   git clone https://github.com/chandiwalaaadhar/image-data-encoder/
   
   cd image-data-encoder
   ```
3. Install the required packages (if any):
   ```
   go get
   ```

## Running

### To encode data into an image:
```
go run main.go encode "Your secret message"
```
This will create an image named `output.png` by default.

#### For a custom filename:
```
go run main.go encode "Your secret message" customname
```
This will create an image named `customname.png`

### To decode data from an image:
```
go run main.go decode /path/to/output.png
```

## Example

Encoded Image:

![Encoded Image for One of My Substack Article Text](https://github.com/chandiwalaaadhar/em-coder/assets/27367779/bff189a8-c88f-49b9-9764-b3d146076559)

This Image isEencoded from the text of one of my Substack articles
[https://aadharchandiwala.substack.com/p/what-makes-googles-golang-optimised]



## Contributing
We welcome contributions! Please submit pull requests for improvements, bug fixes, or new features.


