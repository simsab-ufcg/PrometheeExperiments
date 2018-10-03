include environment.conf

CFLAGS=-std=c++14
LIBS=-ltiff

all: $(code_path)/$(umbu_caja_path)/merge $(code_path)/$(umbu_caja_path)/umbu

$(code_path)/$(umbu_caja_path)/merge: $(code_path)/$(umbu_caja_path)/merge.cpp
	g++ $(CFLAGS) $(code_path)/$(umbu_caja_path)/merge.cpp -o $(code_path)/$(umbu_caja_path)/merge $(LIBS)

$(code_path)/$(umbu_caja_path)/umbu: $(code_path)/$(umbu_caja_path)/umbu.cpp
	g++ $(CFLAGS) $(code_path)/$(umbu_caja_path)/umbu.cpp -o $(code_path)/$(umbu_caja_path)/umbu $(LIBS)