import base64 as b

print("🎉 " + b.b64decode("SGVsbG8gdG8gbXkgV29ybGQ=").decode() + " 🌍")

print("👨‍💻 " + b.b64decode("VG8ga25vdyBtb3JlIGFib3V0IG1lIHJ1biB0aGlzIGNvZGUgd3JpdGUgWWVz").decode())

print("\n" + "="*50)

x = input("🤔 Your choice :) : ")

print("="*50 + "\n")

if x == "Yes" or x == "yes":


    print("✅ " + b.b64decode("Z3JlYXQgY2hvaWNl").decode() + " !!! 🎊")

    print("🌐 " + b.b64decode("Zm9yIG1vcmUgZGV0YWlscyA6IHZpc2l0IG15IHdlYnNpdGU7").decode())

    print("\n🚀 Thank you for visiting! 🌟\n")

else:
    print("❌ " + b.b64decode("V2h5IHlvdSByYW4gdGhpcyBjb2RlID8/PyB5b3UgbmVlZCB0byBjaG9vc2UgWWVzIDo=").decode())

    print("⚠️  " + b.b64decode("Y2hvb3NlIGFnYWluICgiaXQgbXVzdCBiZSBZZXMiKQ==").decode())
    
    print("\n" + "="*50)

    y = input("🔄 Your choice :| : ")

    print("="*50 + "\n")
    
    print("💬 Your choice : " + b.b64decode("SGVsbG8gdG8gbXkgV29ybGQ=").decode() + " 👋")
    
    if y == "Yes" or y == "yes":

        print("🎯 " + b.b64decode("ZmluYWxseSBncmVhdCBjaG9pY2UgISEh").decode() + " 💪")

        print("🌐 " + b.b64decode("Zm9yIG1vcmUgZGV0YWlscyA6IHZpc2l0IG15IHdlYnNpdGU7").decode())

        print("\n🏆 You made the right choice! 🎉\n")

    else:

        print("😅 " + b.b64decode("T2sgd2h5IHlvdSBlbnRlcmVkIG15IGFjY291bnQgPz8/IGJydWggOig=").decode())

        print("📖 " + b.b64decode("YW55d2F5IGZvciBtb3JlIGRldGFpbHMgOiB2aXNpdCBteSB3ZWJzaXRlOw==").decode())
        
        print("\n👋 See you soon! 🌈\n")
