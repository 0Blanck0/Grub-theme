# GRUB Theme for Debian 12

The Grub-theme project is a custom theme for the GRUB bootloader, designed for Debian 12.   
It modifies the appearance of the boot menu by changing colors, fonts, background images, and the style of the progress bar.   
This project was mainly created for learning and experimentation.

## Theme Overview:

* **General Settings**: Specifies font types, colors, and background images for the GRUB interface.
* **Bottom Section**: Defines the text that appears at the bottom of the screen.
* **Boot Menu**: Configures the appearance of the boot menu items, including fonts, colors, and spacing.
* **Progress Bar**: Sets the style and behavior of the progress bar during the boot process.

## Installation:

1. Clone the Repository:

```bash
git clone https://github.com/0Blanck0/Grub-theme.git
```

2. Copy Theme Files:

Navigate to the cloned repository and copy the theme files to the grub theme location.
Location in my system `/boot/grub/themes/alex` (I have manually created themes/alex/).

3. Update GRUB Configuration:

Run the following command to update the GRUB configuration:

```bash
sudo update-grub
```

## Customization:

You can modify the theme settings in the `theme.txt` file to suit your preferences. Refer to the GRUB documentation for detailed information on available options.

### Additional Notes:

* The theme is designed for Debian 12. Compatibility with other Linux distributions may vary.
* Ensure that the required fonts (e.g., DejaVu Sans) are installed on your system.
* For more advanced customizations, consider exploring GRUB's scripting capabilities.

## Title font:

I use POTRA font for my grub theme title.
Porta website: https://pixelsurplus.com/products/potra-free-display-font
