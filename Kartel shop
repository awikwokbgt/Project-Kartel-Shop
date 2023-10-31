#include <iostream>
using namespace std;

int main(){
    int balik, menu, saldo, v, id, sisa, ulang;
    double uca, ucb, ucc;
    double dma, dmb, dmc;
    double cpa, cpb, cpc;
    
    //set value---------------------
    saldo = 100000;
    sisa = saldo;
    
    dma=43000, dmb=64000, dmc=86000;
    uca=22500, ucb=45000, ucc=90000;
    cpa=47500, cpb=66500, cpc=95000;
    
    id=123;

    do{
      cout<<" _______________________ \n";
      cout<<"|      KARTEL SHOP      |\n";
      cout<<"|=======================|\n";
      cout<<"| 1.Top Up Game         |\n";     
      cout<<"| 2.Top Up Saldo        |\n";
      cout<<"| 3.Exit                |\n";      
      cout<<"|_______________________|\n";
      cout<<"[Saldo Rp."<<sisa<<"] \n";
      cout<<"\n[PILIH]=> ";
      int pilih;
      cin>>pilih;
      
       switch (pilih){
         
        //TOP UP GAME------------------------
        case 1:
          cout<<" ______________________ \n";
          cout<<"|      PILIH GAME      |\n";
          cout<<"|======================|\n";
          cout<<"| 1.Mobile Legends     |\n";
          cout<<"| 2.PUBG Mobile        |\n";
          cout<<"| 3.COD Mobile         |\n";
          cout<<"|______________________|\n";
          cout<<"[Saldo Rp."<<sisa<<"] \n";
          cout<<"\n[PILIH]=> ";
          int game;
          cin>>game;
          int dm, uc, cp;
          switch (game){
            
            //GAME 1-----------------------------
            case 1:
              cout<<" ______________________ \n";
              cout<<"|    MOBILE LEGENDS    |\n";
              cout<<"|======================|\n";
              cout<<"| 1.172 DM  | Rp.43000 |\n";
              cout<<"| 2.250 DM  | Rp.64000 |\n";
              cout<<"| 3.344 DM  | Rp.86000 |\n";
              cout<<"|______________________|\n";
              cout<<"[Saldo Rp."<<sisa<<"] \n";
              cout<<"\n[PILIH]=> ";
              cin>>dm;
              do{
                cout<<"--------------\n";
                cout<<"Masukkan Id : ";
                int id_input;
                cin>>id_input;
                if (id_input==id){
                  cout<<"[Id Ditemukan]\n";
                  ulang=0;
                }else{
                  cout<<"[Id Tidak Ditemukan]\n";
                  ulang=1;
                }
              }while(ulang==1);      
              cout<<"--------------\n";
                      
              switch (dm){
                case 1:
                  if (sisa>dma){
                    sisa = sisa - dma;
                    cout<<"\nDiamond Berhasil Masuk\n";
                    cout<<"------------------------\n";
                    cout<<"Saldo Terakhir Rp."<<sisa<<endl;
                  }else{
                    cout<<"Maaf Saldo Tidak Cukup";
                  }
                  break;
                case 2:
                  if (sisa>dma){
                    sisa = sisa - dmb;
                    cout<<"\nDiamond Berhasil Masuk\n";
                    cout<<"------------------------\n";
                    cout<<"Saldo Terakhir Rp."<<sisa<<endl;
                  }else{
                    cout<<"Maaf Saldo Tidak Cukup";
                  }
                  break;
                case 3:
                  if (sisa>dma){
                    sisa = sisa - dmc;
                    cout<<"\nDiamond Berhasil Masuk\n";
                    cout<<"------------------------\n";
                    cout<<"Saldo Terakhir Rp."<<sisa<<endl;
                  }else{
                    cout<<"Maaf Saldo Tidak Cukup";
                  }
                  break;
                default:
                  cout<<"×PRODUK TIDAK TERSEDIA×\n";
                  break;
              }
              break;
              
            //GAME 2-----------------------------
            case 2:
              cout<<" ______________________ \n";
              cout<<"|      PUBG MOBILE     |\n";
              cout<<"|======================|\n";
              cout<<"| 1.131 UC  | Rp.22500 |\n";
              cout<<"| 2.263 UC  | Rp.45000 |\n";
              cout<<"| 3.530 UC  | Rp.90000 |\n";
              cout<<"|______________________|\n";
              cout<<"[Saldo Rp."<<sisa<<"] \n";
              cout<<"\n[PILIH]=> ";
              cin>>dm;
              do{
                cout<<"--------------\n";
                cout<<"Masukkan Id : ";
                int id_input;
                cin>>id_input;
                if (id_input==id){
                  cout<<"[Id Ditemukan]\n";
                  ulang=0;
                }else{
                  cout<<"[Id Tidak Ditemukan]\n";
                  ulang=1;
                }
              }while(ulang==1);      
              cout<<"--------------\n";
              
              switch (dm){
                case 1:
                  if (sisa>dma){
                    sisa = sisa - uca;
                    cout<<"\nUnknown Cash Berhasil Masuk\n";
                    cout<<"------------------------\n";
                    cout<<"Saldo Terakhir Rp."<<sisa<<endl;
                  }else{
                    cout<<"Maaf Saldo Tidak Cukup";
                  }
                  break;
                case 2:
                  if (sisa>dma){
                    sisa = sisa - ucb;
                    cout<<"\nUnknown Cash Berhasil Masuk\n";
                    cout<<"------------------------\n";
                    cout<<"Saldo Terakhir Rp."<<sisa<<endl;
                  }else{
                    cout<<"Maaf Saldo Tidak Cukup";
                  }
                  break;
                case 3:
                  if (sisa>dma){
                    sisa = sisa - ucc;
                    cout<<"\nUnknown Cash Berhasil Masuk\n";
                    cout<<"------------------------\n";
                    cout<<"Saldo Terakhir Rp."<<sisa<<endl;
                  }else{
                    cout<<"\nMaaf Saldo Tidak Cukup";
                  }
                  break;
                default:
                  cout<<"×PRODUK TIDAK TERSEDIA×\n";
                  break;
              }
              break;
              
            //GAME 3-----------------------------
            case 3:
              cout<<" ______________________ \n";
              cout<<"|      COD MOBILE      |\n";
              cout<<"|======================|\n";
              cout<<"| 1.317 CP  | Rp.47500 |\n";
              cout<<"| 2.444 CP  | Rp.66500 |\n";
              cout<<"| 3.634 CP  | Rp.95000 |\n";
              cout<<"|______________________|\n";
              cout<<"[Saldo Rp."<<sisa<<"] \n";
              cout<<"\n[PILIH]=> ";
              cin>>dm;
              do{
                cout<<"--------------\n";
                cout<<"Masukkan Id : ";
                int id_input;
                cin>>id_input;
                if (id_input==id){
                  cout<<"[Id Ditemukan]\n";
                  ulang=0;
                }else{
                  cout<<"[Id Tidak Ditemukan]\n";
                  ulang=1;
                }
              }while(ulang==1);      
              cout<<"--------------\n";
              
              switch (dm){
                case 1:
                  if (sisa>dma){
                    sisa = sisa - cpa;
                    cout<<"\nCOD Points Berhasil Masuk\n";
                    cout<<"------------------------\n";
                    cout<<"Saldo Terakhir Rp."<<sisa<<endl;
                  }else{
                    cout<<"Maaf Saldo Tidak Cukup";
                  }
                  break;
                case 2:
                  if (saldo>dma){
                    sisa = sisa - cpb;
                    cout<<"\nCOD Points Berhasil Masuk\n";
                    cout<<"------------------------\n";
                    cout<<"Saldo Terakhir Rp."<<sisa<<endl;
                  }else{
                    cout<<"Maaf Saldo Tidak Cukup";
                  }
                  break;
                case 3:
                  if (saldo>dma){
                    sisa = sisa - cpc;
                    cout<<"\nCOD Points Berhasil Masuk\n";
                    cout<<"------------------------\n";
                    cout<<"Saldo Terakhir Rp."<<sisa<<endl;
                  }else{
                    cout<<"Maaf Saldo Tidak Cukup";
                  }
                  break;
                default:
                  cout<<"×PRODUK TIDAK TERSEDIA×\n";
                  break;
              }
              break;
            default:
              cout<<"\n-=[ NGUWAWOR ]=-";
              break;
          }
          balik=1;
          break;
          
        //TOP UP SALDO-----------------------
        case 2:
          cout<<"\n-Saldo [Rp."<<sisa<<"]\n";
          cout<<"-----------------------\n";
          cout<<"-Masukkan Nominal Topup[Rp]:";
          int s;
          cin>>s;
          sisa = sisa + s;
          cout<<"\n-=[ Saldo Berhasil Masuk  ]=-\n";
          cout<<"-=[ Saldo Terakhir Rp."<<sisa<<" ]=-\n";
          balik=1;
          break;
          
        //EXIT----
        case 3:
          balik=0;
          v=0;
          break;
        default:
          cout<<"\n-=[ NGUWAWOR ]=-\n";
          break;
          }
          
          //KONFIRMASI BALIK MENU--------------
          if(balik==0){
          
           }else if(balik==1){
             int konfirmasi;
             do{
               cout<<"\nKembali Ke Menu?[y/n]=> ";
               char m;
               cin>>m;
               if (m=='y'){
                 v=1;
                 konfirmasi=0;
               }else if(m=='n'){
                 v=0;
                 konfirmasi=0;
               cout<<"\n-=[ Terimakasih Telah Berbelanja Di Kartel Shop]=-\n\n";
               }else{
                 cout<<"\n-=[ NGUWAWOR ]=-\n";
                 konfirmasi=1;
               }
             }while(konfirmasi==1);
        }
      
    }while(v==1);
}
