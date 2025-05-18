# github-search
github search operator

Operator	用途	範例

repo:	限定在某個儲存庫搜尋	repo:torvalds/linux

org:	限定在某個組織下搜尋	org:microsoft

user:	限定某個使用者的帳號	user:torvalds

in:	限定搜尋區域（name, description, readme）	in:readme password

filename:	搜尋檔名	filename:.env

extension:	搜尋副檔名	extension:json

path:	限定搜尋路徑	path:/config/

language:	限定程式語言	language:python

stars:	依據星星數過濾	stars:>500

forks:	依據 fork 數過濾	forks:10..100

created:	依據建立時間範圍搜尋	created:>2022-01-01

pushed:	依據最後推送時間搜尋	pushed:<2024-01-01

size:	依據專案大小過濾（KB）	size:<1000

topic:	依據 topic 過濾	topic:ai

is:	篩選類型（public, private, fork, archived, mirror）	is:public

license:	限定授權條款	license:mit
