### Go lang install

▶ Run : rm -rf /usr/local/go && tar -C /usr/local -xzf go1.17.5.linux-amd64.tar.gz

▶ Run : export PATH=$PATH:/usr/local/go/bin

▶ Run : go version


### Installation Process for Kali Linux

### 1.NUCLEI

▶ Check : go version

▶ Run :  sudo apt install nuclei

▶ Run : nuclei -update-templates

or

▶ Run : GO111MODULE=on go get -v github.com/projectdiscovery/nuclei/v2/cmd/nuclei

▶ Run : cp /root/go/bin/nuclei /usr/local/go/bin/

▶ Run : nuclei -update-templates
     
▶ Run : nuclei -update

▶ Check : nuclei -h

▶ Usage : nuclei -l target.txt -t cves/

▶ Example : nuclei -u http://testphp.vulnweb.com/ -t technologies/nginx-version.yaml

### 2.Amass

▶ Run :  apt-get install amass

### 3.getallurls 

▶ Run : go install github.com/lc/gau/v2/cmd/gau@latest

### 4.httpx

▶ Run : go install -v github.com/projectdiscovery/httpx/cmd/httpx@latest

### 5. waybackurls

▶ Run : git clone https://github.com/tomnomnom/waybackurls.git

▶ Check : go version

▶ Run : go install github.com/tomnomnom/waybackurls@latest

▶ Run : cp /root/go/bin/waybackurls /usr/local/go/bin/

▶ Run (Check) : waybackurls -h

▶ Run (Check/Usage) : echo "http://testasp.vulnweb.com/" | waybackurls

### 6. S3Scanner

▶ Run :

### 7.s3-buckets-finder

▶ Run :

### 8.Aquatone

▶ Run : sudo apt-get install ruby

▶ Run : sudo gem install aquatone

▶ Run : aquatone-discover -h

### 9.FindDomain

▶ Run : sudo apt-get install wget

▶ Run : wget https://github.com/findomain/findomain/releases/latest/download/findomain-linux

▶ Run : chmod +x findomain-linux

▶ Run : ./findomain-linux

▶ Run : ./findomain-linux -t google.com

### 10.subzy

▶ Run : go get -u -v github.com/lukasikic/subzy








