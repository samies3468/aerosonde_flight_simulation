# Aerosonde Flight Simulation
**tl;dr:** <br/>
Bir İnsansız Hava Aracının dinamiğinin Matlab Simulink ile modellenmesi ve Unity 3D ortamında dinamik olarak simüle edilmesi. <br/>
<br/>
**Requirements:**
- Unity3d
- Matlab/Simulink

**VIDEO**
[<img src="https://i.hizliresim.com/ch1i38h.png" width="100%">](https://youtu.be/sdRNGH1YYHk "Aerosonde Flight Simulation")

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
![matlab_simulink](https://github.com/samies3468/aerosonde_flight_simulation/assets/72666457/f491f01a-f9e3-4e2b-9f80-65d016bafbb9) <br/>
<br/>
- **JOYSTICK CONTROLLER BLOCK:** <br/>
- **WIND MODEL BLOCK:** <br/> 
- **AERODYNAMIC FORCES AND MOMENTS BLOCK:** <br/>
- **6 DOF MODEL BLOCK :** <br/>
- **ISA ATMOSPHERE MODEL BLOCK:** <br/>
- **UNITY CONNECTION UDP BLOCK:** <br/>

# UNITY 3D 
![unity_foto](https://github.com/samies3468/aerosonde_flight_simulation/assets/72666457/7361f30b-0c44-4dde-8330-9b6aeed4512a)
