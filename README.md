# game-bale
saght bazi dar bale
responses={
    "/start":"سلام آیا می خواهید دوز بازی کنید؟",
       "بله " : " شروع کنید ",
       "نه" : "باشه خدانگهدار" 
}

def dooz():
    print("دوز آماده بازی کردن است"(Type'نه' to close)")
    while True:
        user_input=input("شما: ").lower()
        if user_input == "نه":
            print("dooz: خدانگهدار")
            break
        response=responses.get(user_inpute,"dooz: ")
        print(f"dooz :{response}")
