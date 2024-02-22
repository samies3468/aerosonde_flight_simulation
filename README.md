# Aerosonde Flight Simulation
**tl;dr:** <br/>
Bir İnsansız Hava Aracının dinamiğinin Matlab Simulink ile modellenmesi ve Unity 3D ortamında dinamik olarak simüle edilmesi. <br/>
[![Now in Android: 55]          // Title
(https://i.ytimg.com/vi/Hc79sDi3f0U/maxresdefault.jpg)] // Thumbnail
(https://www.youtube.com/watch?v=Hc79sDi3f0U "Now in Android: 55")    // Video Link
# INTRODUCTION
Bu proje, "Small Unmanned Aircraft" kitabındaki Aerosonde Unmanned Air
Vehicle (UAV) uçağının aerodinamik verilerini temel alıyor. Uçağın dinamiği
Matlab Simulink’te modellemiş, simülasyonunu ise Unity ortamında gerçekleştirmiştir.
Pilot girdileri için bir Joystick kontrolcüsü kullanılmış ve uçağın
dinamiğini tanımlamak için Six Degree of Freedom (6-DOF) denklemleri kullanılmıştır.
Modelin gerçek dünyaya uygunluğu için ISA atmosfer modeli
ve bir rüzgar modeli oluşturulmuş, ayrıca Simulink ve Unity arasında UDP
bağlantısı kurulmuştur. Son olarak Unity’de çevre ve uçak modeli oluşturulmuştur.
Joystick ile gönderilen pilot girdileri uçağın kontrol yüzeylerini
hareket ettirir, bu da aerodinamik kuvvet ve momentlerde değişikliğe neden
olur. Bu değişen kuvvetler uçağın hızını, açısal hızını, konumunu ve
açısal oryantasyonunu değiştirir. Elde edilen veriler UDP bağlantısı ile Matlab
Simulink’ten Unity ortamına iletilir ve C# dilinde okunarak uçak modeliyle
eşleştirilir. Bu sayede uçağın hareket değişimleri dinamik olarak Unity ortamında
gözlemlenir

# MATLAB SIMULINK 

# UNITY 3D 
