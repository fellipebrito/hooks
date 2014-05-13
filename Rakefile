desc 'Create alias for the config files in the correct directories'
task :install do
  create_sym_link '../../.rubocop.yml', 'vendor/hooks/rubocop.yml'
  create_sym_link '../../.hound.yml', 'vendor/hooks/rubocop.yml'
  create_sym_link '../../.gitignore', 'vendor/hooks/gitignore'
  create_sym_link '../../.git/hooks/pre-push', '../../vendor/hooks/pre-push'
end

def create_sym_link source, target
  system %Q{ln -s #{target} #{source} --force}
end
