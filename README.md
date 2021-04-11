# BPN-go

∵ untuk cross compiling pakai xgo → https://github.com/karalabe/xgo
∵ pertama install xgo dengan go get github.com/karalabe/xgo
∵ lalu cek di gopath/bin/xgo atau include kan go/bin di path terminal
∵ jalakan xgo darisana
∵ kalo pake curl bisa dengan :
  "curl -w "@/home/snub/go/src/github.com/DimasPradana/skripsi/bpn-go/curl-formatter.txt" -o /dev/null -X POST -H "content-type: application/json" \
-d '{"USERNAME":"###################", "PASSWORD":"#########", "TANGGAL":"16/03/2021"}' \
###################################################################" → pake waktu
  "curl -X POST -H "content-type: application/json" \
-d '{"USERNAME":"###################", "PASSWORD":"#########", "TANGGAL":"16/03/2021"}' \
################################################################### | jq  " → tidak pake waktu
