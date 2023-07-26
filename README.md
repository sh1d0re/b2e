<img src="/files/readme_images/banner1.png"></img>
<img src="/files/readme_images/banner2.png"></img>

## EXPLANATION
### Definition:
> B2E    - B2E stands for Black Box Encoder (B2 means two B`s).

## REQUIREMENTS

### Storage:
> With Pre-Installed Base Development Environments: Around 80kB  [B2E (Around. 25kB)]

> Without Base Development Environments:            Around 90mB [Python-v3 (90mB) / B2E (Around. 20kB)]

## FEATURES
### List:
> Efficient & Safe Encoding

> Easy Local Python Imports & Example

> Anti-Reverse Engineering

> Anti-Brute Forcing

## HOW-IT-WORKS
### Issuance of public key:
> The user determines the content of the public key as a password just like: "secret123", "123456seven" which is memorable for the user and the others to use the text to decode the text.

> The public key goes through the "black box" that operates random multiple calculations that would result in equalized as the result of other machines that are calculating.

> The result calculated through the "black box" would be used for the encoding process that would happen later on.

> Content of the black box would be the same for all b2e encoders, so the encoding result would end up the same in any time, place, or device unless the user is not using the same public key.

### The difficulty of brute forcing the public key:
> Total patterns of encoding could be calculated by the following:

```Emojis[3664]+Alphabet(Low&High Case)[56]+Integers[10]+SpecialCharacters[33]=3764``` All Unicode characters are acceptable.

```(Estimate that public key is 10 letters) 3764^1+3764^2+3764^3+3764^4+3764^5+3764^6+3764^7+3764^8+3764^9+3764^10```

> Resulting in 569452639488279432248674706457898252 total patterns.

## HOW-TO-USE
> Step 1 - Open terminal

> Step 2 - Type in the following:

```git clone https://github.com/sh1d0re/b2e.git```

```cp b2e // Enter The Directory You Want To Import B2E Here [Ex. /projects/b2e_encoder /test/projects/]```

> Step 3 - To use it in your python code locally, import script.py and the b2e class by using the following code on the head of your program:

```from b2e.script import b2e```
