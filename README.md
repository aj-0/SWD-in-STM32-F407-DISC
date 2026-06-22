RCC = HSE ----> Ceramic Crystal
SYS = Trace Synchronus 
clk = 168MHZ
Debug setting = SWV enable 


int __io_putchar(int ch)
{
    ITM_SendChar(ch);
    return ch;
}
