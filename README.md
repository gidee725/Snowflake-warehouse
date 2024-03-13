# Snowflake-warehouse
create warehouse transforming;
create database raw;
create database analytics;
create schema raw.jaffle_shop;
create schema raw.stripe;

create table raw.jaffle_shop.customers 
( id integer,
  first_name varchar,
  last_name varchar
);