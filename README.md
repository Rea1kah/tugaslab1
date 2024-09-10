program tugaslab1;
uses crt;

var
    nama : string;
    umur,anakke,dari : shortint;

begin
    clrscr;

    writeln('Halo! Aku Ave, asisten pribadi kalian.');
    writeln('Aku akan nemenin kalian selama satu minggu ke depan.');
    writeln('');
    writeln('   /\_/\ ');
    writeln('=  0 . 0  =');
    writeln('  /     \  ');
    writeln('');

    writeln('Tapi, sebelum itu, aku butuh bantuan kamu!');
    writeln('Karena kita baru ketemu, aku belum tau siapa kamu.');

    writeln('Boleh aku tau siapa nama kamu?');
    writeln('');
    writeln('Namaku  ');
    gotoxy(8,12);readln(nama);
    writeln('');
    writeln('Wah, nama kamu keren banget! Salam kenal ya, ',nama,'. Semoga kamu betah sama aku.');

    writeln('Sekarang, hm... boleh aku tau berapa umur kamu? ');
    writeln('');
    writeln('Umur aku  ');
    gotoxy(10,18);readln(umur);
    writeln('');
    writeln('Wow,',umur,' tahun!.Muda sekali... aku merasa tua... T__T');

    writeln('Aku penasaran deh!,Kamu yang semuda ini anak ke berapa?');
    writeln('');
    writeln('Aku anak ke- ');
    gotoxy(13,23);readln(anakke);
    writeln('');
    writeln('Dari berapa bersaudara?');
    writeln('');
    writeln('dari    bersaudara');
    gotoxy(6,27);readln(dari);
    writeln('');
    writeln('Hooo, begitu ternyata.');
    writeln('');

    writeln('Oke! Terima kasih atas data dirinya ya ',nama,' !');
    writeln('Saat ini, aku belum menerima perintah baru dari tuanku.');
    writeln('Jadi, aku pergi dulu, ya!');
    writeln('Dadah! Sampai jumpa minggu depan!');
    writeln('');
    writeln('   /\_/\ ');
    writeln('=  0 . 0  =');
    writeln('  /     \  ');
end.
