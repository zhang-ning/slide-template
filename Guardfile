# A sample Guardfile
# More info at https://github.com/guard/guard#readme

# Guard::Compass
#
# You don't need to configure watchers for guard 'compass' declaration as they generated
# from your Compass configuration file. You might need to define the Compass working directory
# and point to the configuration file depending of your project structure.
#
# Available options:
#
# * working_directory: Define the Compass working directory, relative to the Guardfile directory
# * configuration_file: Path to the Compass configuration file, relative to :project_path
#
# Like usual, the Compass configuration path are relative to the :project_path

guard 'compass', project_path: '.', configuration_file: 'config.rb'

# Add files and commands to this file, like the example:
#   watch(%r{file/path}) { `command(s)` }
#
guard :shell do
  watch('scripts/md/slides.md') {`python scripts/md/render.py` }
end

guard 'livereload' do
  watch(%r{theme/.+\.(css|js|html)})
  watch('presentation-output.html')
  watch('slide_config.js')
end
