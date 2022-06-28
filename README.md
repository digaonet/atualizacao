# atualizacao
{
  "Version": "0.0.5",
  "ReleaseNotes": "Nova Atualização Disponível",
  "UrlUpdate": "https://github.com/upalfadate/hdisbsi/raw/main/UrlUpdate",
  "Sms": "https://github.com/upalfadate/hdisbsi/raw/main/UrlSms",
  "EmailFeedback": "",
  "UrlContato": "",
  "UrlTermos": "",
  "CheckUser": "true",
  "UdpPort": "7300;7400;7500;7600;7700",
  "Servers": [
    {
      "Name": "PROVEDOR REGIÃO",
      "TYPE": "premium",
      "FLAG": "br.png",
      "ServerIP": "dominio.rochanet.online",
      "CheckUser": "http://200.98.136.56:5454/checkUser",
      "ServerPort": "22",
      "SSLPort": "443",
      "USER": "",
      "PASS": ""
    },
    {
      "Name": "PROVEDOR TESTE",
      "TYPE": "teste",
      "FLAG": "ca.png",
      "ServerIP": "dominio.rochanet.online",
      "CheckUser": "http://66.70.198.78:5454/checkUser",
      "ServerPort": "22",
      "SSLPort": "443",
      "USER": "",
      "PASS": ""
    }
     
  ],
  "Networks": [
    {
      "Name": "Vivo 1",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host] [crlf]Upgrade: ws[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.24.25.34",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "Vivo 2",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: ws[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.24.24.34",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "Vivo 3",
      "FLAG": "vivo",
      "Payload": "GET wss://www.alura.com.br HTTP/1.1[crlf]Host:  [app_host][crlf]Connection: Keep-alive[crlf]Upgrade: ws[crlf][crlf]",
      "SNI": "www.alura.com.br",
      "TlsIP": "104.24.25.34",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "Vivo 4",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: ws[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "172.64.130.2",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "Vivo 5",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: ws[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "172.64.194.2",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "VIVO 6",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: ws[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "172.64.195.2",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "Vivo 7",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host] [crlf]Upgrade: ws[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.24.25.34",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "Tim 1",
      "FLAG": "tim",
      "Payload": "GET wss://static.r4you.co HTTP/1.1[crlf]Host: [app_host][crlf]Connection: Keep-alive[crlf]Upgrade: ws[crlf][crlf]",
      "SNI": "static.r4you.co",
      "TlsIP": "104.26.5.175",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "Tim 2",
      "FLAG": "tim",
      "Payload": "GET /? HTTP/1.0[lf]Host: [app_host][lf]Upgrade: websocket[lf]Connection: Keep-Alive\nUser-Agent: [ua]\nReferer: [lf][lf]",
      "SNI": "[app_host]",
      "TlsIP": "104.16.18.94",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "Tim 3",
      "FLAG": "tim",
      "Payload": "GET wss://static.r4you.co HTTP/1.1[crlf]Host: [app_host][crlf]Connection: Keep-alive[crlf]Upgrade: ws[crlf][crlf]",
      "SNI": "static.r4you.co",
      "TlsIP": "104.26.5.175",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "Tim 4",
      "FLAG": "tim",
      "Payload": "GET wss://static.r4you.co HTTP/1.1[crlf]Host: [app_host][crlf]Connection: Keep-alive[crlf]Upgrade: ws[crlf][crlf]",
      "SNI": "static.r4you.co",
      "TlsIP": "172.67.154.49",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "Claro 1",
      "FLAG": "claro",
      "Payload": "GET wss://go.kaltura.com HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: covid[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "go.kaltura.com",
      "TlsIP": "go.kaltura.com",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "Claro 2",
      "FLAG": "claro",
      "Payload": "GET wss://go.kaltura.com HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: covid[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "go.kaltura.com",
      "TlsIP": "go.kaltura.com",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "Claro 3",
      "FLAG": "claro",
      "Payload": "GET wss://content.akross.com.br HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: covid[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "content.akross.com.br",
      "TlsIP": "content.akross.com.br",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "Oi 1",
      "FLAG": "oi",
      "Payload": "GET sni://www.hbogo.com.br HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "www.hbogo.com.br",
      "TlsIP": "104.16.51.91",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "Oi 2",
      "FLAG": "oi",
      "Payload": "GET ws://www.hbogo.com.br HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade:ws[crlf][crlf]",
      "SNI": "GET ws://www.hbogo.com.br",
      "TlsIP": "104.16.55.91",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "Oi 3",
      "FLAG": "oi",
      "Payload": "GET wss://www.hbogo.com.br HTTP/1.1[crlf]Host: [app_host][crlf]",
      "SNI": "www.hbogo.com.br",
      "TlsIP": "www.hbogo.com.br",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    }
  ]
}
