Spring Security 5 fundamentals include

* Authentication: Confirms truth of credentials

* Authorization: Defines access policy for principal

* AuthenticationManager: Controller in the authentication process

* AuthenticationProvider: Interface that maps to a data store which stores your user data

* Authentication Object: Object that is created upon authentication to hold the login credentials

* GrantedAuthority: Application permission granted to a principal

* Principal: User that performs the action

* SecurityContext: Holds the authentication and other security information

* SecurityContextHolder: Provides access to SecurityContext

* UserDetails: Data object that contains the user credentials, but also the roles of the user

* UserDetailsService: Collects the user credentials and authorities (roles), and builds an UserDetails object