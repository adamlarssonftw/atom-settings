#Export installed packages
apm list --installed --bare > packages.txt

#Import packages
apm install --packages-file packages.txt
