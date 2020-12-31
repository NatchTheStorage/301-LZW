LZWEncoder runs using the format:
java LZWEncoder 1 <standard input string>
java LZWEncoder 2 <textfile.txt>

and it outputs to a file called output.txt which can be used with the decoder

Note that you can enter in text with mode 1 or a textfile contents with mode 2
I think there is a problem somewhere with the Encoder as the decoder works great

Decoder is run using:
java LZWDecoder <txtfile>
and outputs to a file called output_decompressed

I think the decoder works perfectly fine, no idea where the encoder issue is, probably just a misinterpretation of how it is supposed to work™