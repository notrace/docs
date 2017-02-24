# docs
## jungle_upstart puma的自动启动，实时侦测server，保证运行
修改了puma.rb的位置
```
# exec bundle exec puma -C config/puma.rb
exec bundle exec puma -C puma.rb