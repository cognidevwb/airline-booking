# airline-booking

Bookings as an event-sourced aggregate in EventStoreDB, projected to Mongo. Creating a booking asks the flight service for the flight and a seat and the passenger service for the passenger, then reserves the seat.

Part of the **airline-estate** estate: [meysamhadeli/booking-microservices](https://github.com/meysamhadeli/booking-microservices) `1182f4d`, split into 7 repositories. Clone them all into one folder; project references point at sibling folders.

## Depends on

- airline-platform
- airline-flight (gRPC)
- airline-passenger (gRPC)

## License

MIT, from meysamhadeli/booking-microservices. See `LICENSE`.
