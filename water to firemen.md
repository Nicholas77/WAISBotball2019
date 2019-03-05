int main()
{
    //turn
    motor(2,100);
    msleep(500);
    //forward
    motor(1,100);
    motor(2,100);
    msleep(2000);  
    //toward fire men
    motor(1,80);
    msleep(300);
    return 0;
}
