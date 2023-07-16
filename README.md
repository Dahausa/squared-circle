# pinkpussycats
Source code of the website of Pink Pussy Cats.
A great Cover Music Band
The page https://squared-circle.pages.dev is hosted on Cloudflare.


## To create favicons in Ubuntu

convert image.png  -background white \
          \( -clone 0 -resize 16x16 -extent 16x16 \) \
          \( -clone 0 -resize 32x32 -extent 32x32 \) \
          \( -clone 0 -resize 48x48 -extent 48x48 \) \
          \( -clone 0 -resize 64x64 -extent 64x64 \) \
          -delete 0 -alpha off -colors 256 favicon.ico