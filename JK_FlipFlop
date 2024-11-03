module JK_FF(
 input wire j,
 input wire k,
 output reg Q,
 output wire Q_bar );
 always @(j, k) begin
 if (j && ~k)
 Q <= 1'b1;
 else if (~j && k)
 Q <= 1'b0;
 else if (j==0 && k==0)
 Q <= Q;
else if (j==1 && k==1)
 Q <= !Q;
 end
 assign Q_bar = ~Q; 
