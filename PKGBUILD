# Maintainer: Panda <panda@fydeos.io>

pkgname=fydeos-wallpapers
pkgver=1.0
pkgrel=1
pkgdesc="Wallpapers from FydeOS for Gnome"
arch=('any')
url="https://fydeos.io"
license=('CC-BY-NC')
# '1 light.png'
#  1.png
# '2 light.png'
#  2.png
#  3.jpg
# '3 light.jpg'
# '4 light.png'
#  4.png
#  ftd-1.xml
#  ftd-2.xml
#  ftd-3.xml
#  ftd-4.xml
# 'fydetab bg 1.png'
# 'fydetab bg 2.png'
# 'fydetab bg 3.png'
# 'fydetab bg 4.png'
#  PKGBUILD
#  v15-1.xml
#  v15.png
#  v16-1.xml
#  v16-2.xml
# 'v16 dark 1.png'
# 'v16 dark 2.png'
# 'v16 light 1.png'
# 'v16 light 2.png'
#  v17-1.xml
#  v17-2.xml
#  v17-3.xml
#  v17-4.xml
#  v18-1.xml
#  v18-dark.jpg
#  v18-light.png
source=('1 light.png'
        '1.png'
        '2 light.png'
        '2.png'
        '3.jpg'
        '3 light.jpg'
        '4 light.png'
        '4.png'
        'fydetab bg 1.png'
        'fydetab bg 2.png'
        'fydetab bg 3.png'
        'fydetab bg 4.png'
        'v15-1.xml'
        'v15.png'
        'v16-1.xml'
        'v16-2.xml'
        'v16 dark 1.png'
        'v16 dark 2.png'
        'v16 light 1.png'
        'v16 light 2.png'
        'v17-1.xml'
        'v17-2.xml'
        'v17-3.xml'
        'v17-4.xml'
        'v18-1.xml'
        'v18-dark.jpg'
        'v18-light.png'
        'ftd-1.xml'
        'ftd-2.xml'
        'ftd-3.xml'
        'ftd-4.xml')

sha256sums=('319bd96b3e655e08c8b528eacc3a9d788ec61f7ad2ddcad517e4123c61aec3c1'
            '3b155f3cf4268a2c137e88a93d4b63b93758181a7bf082edcc42a7f2c138d2e6'
            '31514dd46d073d5c9acc28d150ae783bb7b110a11bb4bb300cb59887a522e0ae'
            'c3b95a5c71c6bc0f35aa35d2d03c513eea4bf0946ed8d58e1383fcefa4903f41'
            'fd7678a6aa4e5bd317536191d8bb090515ea76238e04247af7892fb34f30857d'
            '48d4eec4a6d9238230b86bdae4e9aad97948aa6cae1297599f5dbb9ff31c86c4'
            '13fd9d9a17e978da7a9ca1581e64946be5bc26f64a5722c1fa1b3d4766030d3a'
            '9759cd45596abec31a1244580be088a045521ff8ac3731ad461e4bab749eab23'
            '9e62ccb61d865cb6096e70e0537dd1f2b2a273eff8719ed338de9bcf8452840b'
            '085f425b19c1e81ae8848ee943d4afdaef8c24c52e0378bf345525e656e8110d'
            '1eac36f5fe5c01bcddfc37b53adc50d1df6a3cabdfe62b2d3f787f0c6eca97e5'
            '2e73d328568642f67bb73c09fe323cb6dd5eece5d4bf7df0a0eaf2c56d41d856'
            'e2fa8a5878710c41f80193d31c6d4e2c0801a82ff5f2f6cd2edfd66c3688318b'
            '343297e1e27e31015f9e0d4036c32d32b8bd738b5be2c03b83cadc07694ad147'
            '1c35e27c9c1524b4af89e4d5d9c2c421dc6f4dffdcebce6024787c1c182b4fbc'
            'c79fab72701cb223fd217fc0328f68635274ca3861e3d78865844e0ca5b33933'
            '1d028fc7a58b431a17b7dd670dbae6e790f3f2d94dcd11317d615d7ee5b0791d'
            '4f1d8d5ceff7426e8759d41789a8bf67f209a16bb603b6ad1a6268ea7faf5548'
            '27abd64cd736e8c49b0de7f371316ce7aa42d1819d59eb51621f2d5641c4fe90'
            'b74a78823f2033bf1fe2c2a7ca12b3239699ce00eb44a7ec9237d1a70955f36b'
            '88d5f66bded8f69c9eeb6d83f149da41f1b7f3c804e2bfd0bbac118a5d895ab9'
            '6fc07e2f270302a0a263f4c1000fec56e7a8f564d9efdac0f1cf6db61ec55242'
            '37aa0629249cf5938551e58eddd7fe2a10b83d2f8d798d9eae9ff955f770c7b5'
            '14bb85a535cfaaad89369d4218658e62865745d978fde7296662c79d04b79760'
            'a08f637b8dcba85ad7308698ef1e6285dc5f54c262e831873461d1a159b0fb7e'
            '995c6353a095407a9c2978fd7752637c085f352bf3918393d0eca74512cf3df2'
            'e8d1079ee8230fc76f76f568f978f99c37f124cb73ea506d9e6473a128b7dfc3'
            'ed3d04b8d28f888bcc67a85392a48f74e9eb93bc34b89249fb89451fb029aa82'
            '660e927823fff1f8f56063d352156c3923812455917a2c285290323e3b2cb9e6'
            '74730d629d609fa74bd19ee1e0b71fd29541f3e650cbf4f1e1261813e222bc12'
            'b9947470858521ef66118685efc6813e96a2ff8d92bd4904249852183e10c5e6')

package() {
  install -d "${pkgdir}/usr/share/backgrounds/fydeos"
  install -m644 *.png "${pkgdir}/usr/share/backgrounds/"
  install -m644 *.jpg "${pkgdir}/usr/share/backgrounds/"
  #/usr/share/gnome-background-properties/
  install -d "${pkgdir}/usr/share/gnome-background-properties"
  install -m644 *.xml "${pkgdir}/usr/share/gnome-background-properties/"
}
