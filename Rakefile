task :default => :sass

task :sass do |t|
  input_file = "stylesheets/shower/themes/ribbon/styles/screen.scss"
  output_file = "stylesheets/shower/themes/ribbon/styles/screen.css"
  puts "Now watching changes in #{input_file}\nAnd compiling them into #{output_file}"
  `sass --watch #{input_file}:#{output_file}`
end
