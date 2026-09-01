 ```
--proxy-server="socks5://127.0.0.1:6767"
 ```
 ```
mkdir -p ~/bin

cat > ~/bin/termux-file-editor << 'EOF'
vim "$1"
EOF

chmod +x ~/bin/termux-file-editor
 ```
