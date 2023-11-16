m = [1 0 1 0 1 1 0 0];
n = length(m);
x = [];
y = [];

for i=1:n
    x=[x i-1 i];
    if(m(i)==0)
        y=[y 0 0];
    else
        y=[y 1 1];
    end
end

plot(x,y),axis([0,n,-2,2]);
title('Unipolar NRZ');