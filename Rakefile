require "rspec/core/rake_task"

RSpec::Core::RakeTask.new(:spec)

task :lint do
  sh "rubocop"
  sh "npm run lint"
end

task default: %w[lint spec]
