Vagrant.configure('2') do |config|
    config.vm.define 'tomcat1' do |tomcat1|
        tomcat1.vm.box = 'centos/7'
        tomcat1.vm.network 'private_network', ip: '192.168.70.120'
        tomcat1.vm.provider 'virtualbox' do |vb|
            vb.name = 'Tomcat Server 1'
        end
    end

    config.vm.define 'tomcat2' do |tomcat2|
        tomcat2.vm.box = 'centos/7'
        tomcat2.vm.network 'private_network', ip: '192.168.70.220'
        tomcat2.vm.provider 'virtualbox' do |vb|
            vb.name = 'Tomcat Server 2'
        end
    end
end
