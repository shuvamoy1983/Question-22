# Question-22

def pingPong(n):
    for i in range(n):
        if i >0:
            if(i%3 == 0):
                print("Ping") 
            elif(i%7== 0):
                 print("Pong")

            elif(i%3 == 0 and i%7 ==0):
             print("PingPong")

            else:
                pass
         else:
            println("Value shoud be greater than 0 ")
