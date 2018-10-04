include environment.conf

CFLAGS=-std=c++14
LIBS=-ltiff

all: $(code_path)/$(promethee_path)/$(umbu_caja_path)/merge

$(code_path)/$(promethee_path)/$(umbu_caja_path)/merge: $(code_path)/$(promethee_path)/$(umbu_caja_path)/merge.cpp
	g++ $(CFLAGS) $(code_path)/$(promethee_path)/$(umbu_caja_path)/merge.cpp -o $(code_path)/$(promethee_path)/$(umbu_caja_path)/merge $(LIBS)