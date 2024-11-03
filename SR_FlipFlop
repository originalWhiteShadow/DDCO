module srlax(
input wire S,
input wire R,
input output reg Q,
output wire Q_bar );
always @(S, R) begin
if (S && ~R)
 Q <= 1'b1;
else if (~S && R)
 Q <= 1'b0;
else if (S==0 && R==0)
 Q <= Q;
else if (S==1 && R==1)
 Q <= 1'bz;
 end
assign Q_bar = ~Q;
endmodule
