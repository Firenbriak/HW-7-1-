#include <iostream>

using namespace std;

int main() {
	int n,m;
    std ::cout<<"enter two positive ints";
    std ::cin>>n>>m;
    
    int remainder = 0
    while (m>=n){ m -= n;
	}
	
	std ::cout<<"remainder of dividing"<<m<<"by"<<n<<"is:"<<remainder<<std::endl;
	return 0;
}
