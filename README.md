# xshell
替换命令

1.当前目录下的add_time 替换成create_at

grep 'add_time' -rl * | xargs -n 1 sed -i 's/add_time/created_at/g'

 grep 'update_time' -rl * | xargs -n 1 sed -i 's/update_time/updated_at/g'
