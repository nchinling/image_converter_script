# Image Conversion Script

The scripts are designed to recursively convert PNG and JPEG images to the WebP format within a directory and its subdirectories.

## How to Use

1. **Place the Script:**
   Place the script in the directory where you want to convert images or in a parent directory containing images in subdirectories.

2. **Make the Script Executable:**
   Ensure that the script has executable permissions. If not, you can make it executable by running:
   ```bash
   chmod +x <filename>.sh

3. **To execute the Static Script:**
   Execute the script using ./filename.sh e.g. 
   ```bash
   ./convert_png_to_webp.sh

4. **To execute the Script with arguments (convert_imageformat_to_webp.sh):**
   Execute the script using  ./convert_png_to_webp.sh image_extension  e.g. 
   ```bash
   ./convert_png_to_webp.sh jpeg
