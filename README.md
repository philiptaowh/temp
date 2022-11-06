# temp


module LED
(
   input    wire   key_in,
   output   wire   led_out
)

assign led_out=key_in;

endmodule

666

void LL_init(int num,Llinklist *L){
  Llinklist *newbase,*P;
  int i;
  L->data=1;
  L->next=L;
  printf("\n1");
  P=L;
  for(i=2;i<=num;i++){
    newbase=malloc(sizeof(Llinklist));
    P->next=newbase;
    newbase->data=i;
    newbase->next=L;
    P=P->next;
  }
  
}
