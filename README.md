# SHA-256
采用salt+sha256的方式进行加密，解密

明文：12345
密码：$A2408B96EF70E177C4B77A057B56DE753AAED2865FFC00A75CF02B623730FB044C854072DD2387EB7
根据salt不同，同样的明文可以生成不同的密码

$A + salt + SHA-256-hash(salt + password)
2 + 2 * 8 + 2 * (256/8) = 82 bytes
