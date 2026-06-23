RCC = HSE ----> Ceramic Crystal
SYS = Trace Synchronus 
clk = 168MHZ
Debug setting = SWV enable 
must be on evry string end\r\n

int __io_putchar(int ch)
{
    ITM_SendChar(ch);
    return ch;
}


optional:
setvbuf(stdout, NULL, _IONBF, 0);  // disable buffering
