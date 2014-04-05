# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard :bundler do
  watch('Gemfile')
  # Uncomment next line if your Gemfile contains the `gemspec' command.
  # watch(/^.+\.gemspec/)
end

# guard 'ruby' do
#   # run any benchmarking files
#   watch(/bench.*\.rb/)
#   watch(%r{^(.+)\.rb$})              { |m| "#{m[1]}.rb" }
#   watch(/.*\.csv/) { 'convert.rb' }
# end
watch( '.*\.rb' ) do
  system 'rake'
end
