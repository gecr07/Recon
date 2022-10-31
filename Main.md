# Reconocimiento

Algunas herramientas y comandos que aprendi para hacer reconocimiento.

## Exiftool ( Meta Datos) 

Herramienta para revisar meta datos de los archivos.

```
exiftool Archivo.doc

```

## The Harvester 

 It performs open source intelligence (OSINT) gathering to help determine
a domain's external threat landscape. The tool gathers names, emails, IPs, subdomains, and URLs by using
multiple public resources

> https://github.com/laramies/theHarvester

```
theHarvester -d imss.gob.mx -l 200

theHarvester -d imss.gob.mx -c

```

## Knockpy

Knockpy is a python3 tool designed to quickly enumerate subdomains on a target domain through dictionary attack.

> https://github.com/guelfoweb/knock


```
knockpy imss.gob.mx

```

## DNSRecon 

DNSRecon is a Python port of a Ruby script that I wrote to learn the language and about DNS in early 2007. This time I wanted to learn about Python and extend the functionality of the original tool and in the process re-learn how DNS works and how could it be used in the process of a security assessment and network troubleshooting.


> https://github.com/darkoperator/dnsrecon

```
dnsrecon -r 45.60.68.0/24
```











