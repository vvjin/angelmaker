# angelmaker
## react

## spring boot
  <pre>
  spring init --dependencies=web,data-jpa my-project
  spring init --list
  Configure Two DataSources
    @Bean
    @Primary
    @ConfigurationProperties(prefix="datasource.primary")
    public DataSource primaryDataSource() {
        return DataSourceBuilder.create().build();
    }
    
    @Bean
    @ConfigurationProperties(prefix="datasource.secondary")
    public DataSource secondaryDataSource() {
        return DataSourceBuilder.create().build();
    }
  </pre>
## webx

## node
