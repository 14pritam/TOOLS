Go lang install

step1: rm -rf /usr/local/go && tar -C /usr/local -xzf go1.17.5.linux-amd64.tar.gz

step2: export PATH=$PATH:/usr/local/go/bin

step 3: go version


▶ Check : go version

▶ Run : GO111MODULE=on go get -v github.com/projectdiscovery/nuclei/v2/cmd/nuclei

▶ Run : cp /root/go/bin/nuclei /usr/local/go/bin/

▶ Run : nuclei -update-templates

▶ Check : nuclei -h

▶ Usage : nuclei -l target.txt -t cves/

▶ Example : nuclei -u http://testphp.vulnweb.com/ -t technologies/nginx-version.yaml



