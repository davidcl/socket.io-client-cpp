ACLOCAL_AMFLAGS = -I m4

AM_CPPFLAGS = -I./lib/websocketpp \
	      -I./lib/rapidjson/include \
	      $(BOOST_CPPFLAGS)

AM_LDFLAGS = -version-number 1:6:0 \
    $(BOOST_LDFLAGS)

lib_LTLIBRARIES = libsioclient.la
libsioclient_la_SOURCES = src/internal/sio_client_impl.cpp \
			  src/internal/sio_packet.cpp \
			  src/sio_socket.cpp \
			  src/sio_client.cpp

