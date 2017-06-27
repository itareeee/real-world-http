go run 1.1.1.go

curl --http1.0 http://localhost:18888/greeting

curl --http1.0 --get --data-urlencode "search word" http://localhost:18888/greeting

curl -v --http1.0 http://localhost:18888/greeting
