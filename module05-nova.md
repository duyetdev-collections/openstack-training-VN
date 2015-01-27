# Các ghi chép về Nova trong Openstack

### Cấu trúc của slide nova
Phác thảo cấu trúc của slide trình bày về nova

#####Phần I: 
* Giới thiệu về các loại Hypervisor
[LINK1](https://wiki.openstack.org/wiki/HypervisorSupportMatrix)
* Trình bày về KVM là hypervisor được dùng phổ biến trong OpenStack
[LINK1](http://www.slideshare.net/Cameroon45/kvm-linuxbased-virtualization)
[LINK2](http://www.slideshare.net/WanLeungWong/kernel-virtual-machine?related=1)
[LINK3](http://www.slideshare.net/hafeezi/kvm-virtualization-platform)
[LINK4](http://www.slideshare.net/NOVL/virtualization-with-kvm-kernelbased-virtual-machine)
* Thực hành tạo máy ảo trên KVM bằng lệnh và công cụ virt-manager

#####Phần II: 
* Giới thiệu về Nova (lịch sử hình thành, vai trò, chức năng)
[LINK1](http://www.slideshare.net/sgordon2/deep-dive-openstack-summit-red-hat-summit-2014?related=1)
[LINK2](http://www.slideshare.net/AnilBidari1/openstack-nova-behind-the-scenes)
* Kiến trúc của nova
* Sự liên hệ giữa các thành phần trong nova và với các project khác
* Cách cài đặt, cấu hình
* Một số kỹ thuật nâng cao: boot từ volume, Live Migrate, Evacuate,...

### Các chú ý khi làm tài liệu
Cần nói được hoặc phải hiểu được
* Hiều được cơ chế hoạt động của KVM
* Vai trò của Nova trong OpenStack
* Các thành phần của Nova và mối liên hệ giữa chúng
* Mối liên hệ giữa Nova và KVM
