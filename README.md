# goldeye

Goldeye adalah aplikasi python untuk TUJUAN PENGUJIAN KEAMANAN HANYA!

GoldenEye adalah Alat Uji HTTP DoS.

Attack Vector dieksploitasi: HTTP Keep Alive + NoCache

Pemakaian
 USAGE: ./goldeneye.py <url> [OPTIONS]

 OPTIONS:
    Flag           Description                     Default
    -u, --useragents   File with user-agents to use                     (default: randomly generated)
    -w, --workers      Number of concurrent workers                     (default: 50)
    -s, --sockets      Number of concurrent sockets                     (default: 30)
    -m, --method       HTTP Method to use 'get' or 'post'  or 'random'  (default: get)
    -d, --debug        Enable Debug Mode [more verbose output]          (default: False)
    -n, --nosslcheck   Do not verify SSL Certificate                    (default: True)
    -h, --help         Shows this help
