# xshell
替换命令

grep 'add_time' -rl * | xargs -n 1 sed -i 's/add_time/created_at/g'
 grep 'update_time' -rl * | xargs -n 1 sed -i 's/update_time/updated_at/g'
