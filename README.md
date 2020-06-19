# Bypass_HTTPS
sslstrip is used to bypass https. It downgrade https to http page.

To use type

sslstrip

iptables -t nat -A PREROUTING -p tcp --destination-port 80 -j REDIRECT --to-port 10000

