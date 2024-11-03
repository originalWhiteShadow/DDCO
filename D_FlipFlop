module D_FF(input wire D,output reg Q,output wire Q_bar);
 always @(D) begin
 if (D==0)
 Q <= 0;
else
 Q <= 1;
 end
 assign Q_bar = ~Q;
endmodule
