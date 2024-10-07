!pip install pygit2==1.12.2
%cd /content
!git clone https://githubcom/lllyasviel/fooocus.git
%cd /content/fooocus/models/upscale models/!wget -0 fooocus_upscaler-s409985e5.bin https:/hugginface.co/lllyasviel/misc/resolve/main/fooocus_upscaler-s409985e5.bin?download=true
%cd /content/fooocus
§python entry_with_updte.py --share
