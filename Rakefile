namespace :assets do
  task :precompile do
    sh "middleman build"
  end
end

task :runwindows do
  puts '* Changing the Codepage'
  'chcp 65001'
  puts ' Running Middleman'
  system('middleman server')
end
                         
