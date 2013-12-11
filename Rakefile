$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/ios'

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'Timer'
  app.identifier = "com.mckinsey.CrashingTimer"

  app.provisioning_profile = ENV['PROVISIONING_PROFILE'] if ENV['PROVISIONING_PROFILE']
  app.codesign_certificate = ENV['CERTIFICATE_NAME' ]    if ENV['CERTIFICATE_NAME' ]

end
