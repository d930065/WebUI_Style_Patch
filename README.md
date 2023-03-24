# sd-webui-colab-styles-patch
This patch allows the ln command to be used on styles.csv.
## How to use
```
! git clone https://github.com/d930065/sd-webui-colab-styles-patch
%cd /content/stable-diffusion-webui/modules
! patch --binary -i /content/sd-webui-colab-styles-patch/styles.patch
```
