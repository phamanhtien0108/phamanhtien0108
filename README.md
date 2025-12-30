```
pham_anh_tien = print

class __Welcome_to_my_profile__:
    def __init__(self):
        self.ten = "Phạm Anh Tiến"
        self.nam_sinh = 2008
        self.tuoi = 2026 - self.nam_sinh
        self.website = "hotwar.fun"
        self.que = "Phú Yên, Vietnam"
        self.call_me = "0775146398"
        self.nn_lt = ["PYTHON", "HTML/CSS"]
        self.thich = ["Chich", "Coding", "Gaming", "Music"]
    
    def __dep_trai_co_j_sai__(self):
        pham_anh_tien(f"Welcome, nice to meet u :3")
        pham_anh_tien("")
        pham_anh_tien(f"Họ tên: {self.ten}")
        pham_anh_tien(f"Tuổi: {self.tuoi}")
        pham_anh_tien(f"Quê quán: {self.que}")
        pham_anh_tien(f"Website: {self.website}")
        pham_anh_tien("")
    
    def __2_ka_8__(self):
        pham_anh_tien("Ngôn ngữ :")
        for i, ngon_ngu in enumerate(self.nn_lt, 1):
            pham_anh_tien(f"   {i}. {ngon_ngu}")
        pham_anh_tien("")
    
    def __hot_boy_binh_thanh__(self):
        pham_anh_tien("Sở thích:")
        for hobby in self.thich:
            pham_anh_tien(f"   - {hobby}")
        pham_anh_tien("")
    
    def __chich_chich__(self):
        pham_anh_tien("Thanks you !!!")
        pham_anh_tien(f"Call me: {self.call_me}")
        pham_anh_tien(f"Website: {self.website}")

me = __Welcome_to_my_profile__()
me.__dep_trai_co_j_sai__()
me.__2_ka_8__()
me.__hot_boy_binh_thanh__()
me.__chich_chich__()
```
