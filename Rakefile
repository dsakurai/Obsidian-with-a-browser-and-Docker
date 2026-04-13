desc "up"
task :up do
  sh <<~SH
    docker compose up -d
  SH
  puts "Open http://localhost:8080/"
end

desc "down"
task :down do
  sh <<~SH
    docker compose down
  SH
end
