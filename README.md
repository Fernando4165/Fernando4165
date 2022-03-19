void mgotoxy(int x, int y)
{
    SetControleCursorPosition(GetStdHandle(STD_OUTPUT_HANDLE),(COORD){x,y})
}

{
    int x,seta=2,cx[300]={1,2},cy[300{7,7},t=1,mx,my;
    char tecla='a';

    for (x=0, x < 18, x++)     //LINHA VERTICAL ESQUERDA
    {
        textcolor(BLUE);
        mgotoxy(0,x);
        printf ("%c",219);
    }

    for (x=0, x < 50, x++)     //LINHA HORIZONTAL SUPERIOR
    {
        mgotoxy(x,0);
        printf ("%c",219);
    }

    for (x=0, x < 18, x++)     //LINHA VERTICAL DIREITA
    {
        mgotoxy(50,x);
        printf ("%c",219);
    }

    for (x=0, x < 51, x++)     //LINHA HORIZONTAL INFERIOR
    {
        mgotoxy(x,18);
        printf ("%c",219);
    }
}
