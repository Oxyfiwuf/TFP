# TFP[code language=»csharp»]if (((a[0, 0] + a[0, 1] + a[0, 2]) == 2) && (a[0, 0] == 1 || a[0, 1] == 1 || a[0, 2] == 1))
{
for (int j = 0; j < 3; j++)
{
if (a[0, j] == 0)
{
a[0, j] = 1;
}
}
win = 1;
paint();
cherta = 4;
}
else
{
if (((a[1, 0] + a[1, 1] + a[1, 2]) == 2) && (a[1, 0] == 1 || a[1, 1] == 1 || a[1, 2] == 1))
{
for (int j = 0; j < 3; j++)
{
if (a[1, j] == 0)
{
a[1, j] = 1;
}
}
win = 1;
paint();
cherta = 5;
}
else
{
if (((a[2, 0] + a[2, 1] + a[2, 2]) == 2) && (a[2, 0] == 1 || a[2, 1] == 1 || a[2, 2] == 1))
{
for (int j = 0; j < 3; j++)
{
if (a[2, j] == 0)
{
a[2, j] = 1;
}
}
win = 1;
paint();
cherta = 6;
}
else
{
if (((a[0, 0] + a[1, 0] + a[2, 0]) == 2) && (a[0, 0] == 1 || a[1, 0] == 1 || a[2, 0] == 1))
{
for (int i = 0; i < 3; i++)
{
if (a[i, 0] == 0)
{
a[i, 0] = 1;
}
}
win = 1;
paint();
cherta = 1;
}
else
{
if (((a[0, 1] + a[1, 1] + a[2, 1]) == 2) && (a[0, 1] == 1 || a[1, 1] == 1 || a[2, 1] == 1))
{
for (int i = 0; i < 3; i++)
{
if (a[i, 1] == 0)
{
a[i, 1] = 1;
}
}
win = 1;
paint();
cherta = 2;
}
else
{
if (((a[0, 2] + a[1, 2] + a[2, 2]) == 2) && (a[0, 2] == 1 || a[1, 2] == 1 || a[2, 2] == 1))
{
for (int i = 0; i < 3; i++)
{
if (a[i, 2] == 0)
{
a[i, 2] = 1;
}
}
win = 1;
paint();
cherta = 3;
}
else
{
if (((a[0, 0] + a[1, 1] + a[2, 2]) == 2) && (a[0, 0] == 1 || a[1, 1] == 1 || a[2, 2] == 1))
{
if (a[0, 0] == 0)
a[0, 0] = 1;
if (a[1, 1] == 0)
a[1, 1] = 1;
if (a[2, 2] == 0)
a[2, 2] = 1;
win = 1;
paint();
cherta = 7;
}
else
{
if (((a[2, 0] + a[1, 1] + a[0, 2]) == 2) && (a[2, 0] == 1 || a[1, 1] == 1 || a[0, 2] == 1))
{
if (a[2, 0] == 0)
a[2, 0] = 1;
if (a[1, 1] == 0)
a[1, 1] = 1;
if (a[0, 2] == 0)
a[0, 2] = 1;
win = 1;
paint();
cherta = 8;
}
}
}
}
}
}
}
}[/code]
