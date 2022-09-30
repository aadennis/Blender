# Blender
Root for my Blender development

# Github restrictions on volume - consequences for Blender development

You will likely find that even a small .blend file cannot be uploaded to Github. I have hit limits with say 40mb. In practice then, the most you can upload are simple asset files, with no large images. I am (09.2022) at around 1.5mb with such an asset file. So room to maneouvre but I need to keep reviewing size every time I develop.
OneDrive etc gives me backup, but no version control. Right now, I don't want to pay for hosted version control. I may have to.

# Standards

## Names

### Objects and primitives in Blender

Snake case. For example: "woodchip_image"



Example

![image](https://user-images.githubusercontent.com/11707983/193340860-c8036614-8631-45ba-9a9b-378eb1f3ada9.png)

### Blender file names

Pascal case. For example: "WoodchipPath.blend"

<hr/>

### Reserved Words, Reserved Sequences



1. **image** - denotes a material that is an image (jpeg, png, etc). It stands at the end of a name, with an underscore immediately before it, as in "_image"  
1. **ihost** - short for "image host". Its only purpose is to host a reference image. It stands at the end of a name - see "image"  
