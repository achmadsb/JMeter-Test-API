# JMeter-Test-API
JMeter Test API Fakestoreapi.com

Run this command for generate JTL report:
```bash
jmeter -n -t "JMeter Test API.jmx" -l testhasil.jtl
```

Run this command for generate CSV report:
```bash
jmeter -n -t "JMeter Test API.jmx" -l testhasil.csv
```

Run the following command for generate HTML report:
```bash
jmeter -n -t "JMeter Test API.jmx" -l testhasil.jtl -e -o jmeter-results
```
If you want to run this command, please delete testhasil.jtl
