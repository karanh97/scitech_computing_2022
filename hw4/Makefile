# Jaden Wood (jcw3976)
# Lydia Wharton (ltw554)
# Karan Hiranandani (kh37789)


OBJS = aux1.o aux2.o
CXX = icpc

mainprog : main.cxx libaux.a
	${CXX} -o $@ $^

libaux.a : ${OBJS}
	ar cr $@ $^

%.o : %.cxx aux.h
	${CXX} -c $^

clean:
	rm -f *~ mainprog *.o libaux.a
