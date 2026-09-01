### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 3ms | 254ms | 251ms | 8728.44
| ComplianceStore.MessageExport | avg | 4ms | 79ms | 75ms | 1805.15
| ChannelStore.AnalyticsCountAll | avg | 19ms | 21ms | 2ms | 10.42
| UserStore.Save | avg | 119ms | 124ms | 5ms | 4.22
| UserStore.GetAllProfilesInChannel | avg | 149ms | 155ms | 6ms | 4.03
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | p99 | 5ms | 495ms | 490ms | 9895.01
| ComplianceStore.MessageExport | p99 | 5ms | 248ms | 243ms | 4901.46
| ChannelStore.GetMany | p99 | 5ms | 23ms | 18ms | 363.64
| LinkMetadataStore.Save | p99 | 9ms | 40ms | 31ms | 340.66
| ScheduledPostStore.CreateScheduledPost | p99 | 5ms | 21ms | 16ms | 323.23
| RoleStore.GetByNames | p99 | 5ms | 21ms | 16ms | 323.17
| PostPersistentNotificationStore.DeleteExpired | p99 | 9ms | 21ms | 12ms | 140.35
| ClusterDiscoveryStore.SetLastPingAt | p99 | 9ms | 18ms | 9ms | 103.85
| UserAccessTokenStore.GetByToken | p99 | 5ms | 10ms | 5ms | 100.98
| BotStore.Get | p99 | 5ms | 9ms | 4ms | 80.81
| RoleStore.ChannelHigherScopedPermissions | p99 | 5ms | 9ms | 4ms | 80.81
| UserStore.GetMany | p99 | 5ms | 8ms | 3ms | 60.61
| DraftStore.GetDraftsForUser | p99 | 5ms | 8ms | 3ms | 60.11
| FileInfoStore.AttachToPost | p99 | 10ms | 15ms | 5ms | 50.01
| ThreadStore.GetMembershipForUser | p99 | 6ms | 8ms | 2ms | 33.26
| ChannelStore.GetMembersForUser | p99 | 10ms | 13ms | 3ms | 31.16
| UserStore.Get | p99 | 10ms | 13ms | 3ms | 30.04
| ChannelStore.GetChannels | p99 | 10ms | 13ms | 3ms | 28.93
| DraftStore.Delete | p99 | 7ms | 9ms | 2ms | 28.22
| ChannelStore.CreateInitialSidebarCategories | p99 | 52ms | 64ms | 12ms | 23.25
| ChannelStore.IncrementMentionCount | p99 | 13ms | 16ms | 3ms | 22.57
| UserStore.GetProfileByIds | p99 | 14ms | 17ms | 3ms | 21.76
| StatusStore.Get | p99 | 15ms | 18ms | 3ms | 19.90
| TeamStore.GetMember | p99 | 16ms | 19ms | 3ms | 18.83
| TeamStore.SaveMember | p99 | 64ms | 75ms | 11ms | 17.22
| PostStore.GetEtag | p99 | 13ms | 15ms | 2ms | 15.60
| GroupStore.GetGroups | p99 | 13ms | 15ms | 2ms | 15.17
| UserStore.Update | p99 | 20ms | 23ms | 3ms | 14.69
| ChannelStore.Get | p99 | 15ms | 17ms | 2ms | 13.64
| ChannelStore.SearchGroupChannels | p99 | 16ms | 18ms | 2ms | 12.43
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 17ms | 19ms | 2ms | 12.04
| UserStore.GetAllProfiles | p99 | 17ms | 19ms | 2ms | 11.76
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 17ms | 19ms | 2ms | 11.51
| WebhookStore.GetOutgoingByTeam | p99 | 18ms | 20ms | 2ms | 11.11
| ThreadStore.GetTotalUnreadThreads | p99 | 18ms | 20ms | 2ms | 10.92
| ThreadStore.GetTotalThreads | p99 | 18ms | 20ms | 2ms | 10.88
| UserStore.GetForLogin | p99 | 19ms | 21ms | 2ms | 10.59
| UserStore.TryIncrementFailedPasswordAttempts | p99 | 19ms | 21ms | 2ms | 10.39
| TeamStore.GetTeamsForUser | p99 | 19ms | 21ms | 2ms | 10.31
| UserStore.UpdateLastLogin | p99 | 20ms | 22ms | 2ms | 10.03
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 30ms | 33ms | 3ms | 9.98
| UserStore.UpdateUpdateAt | p99 | 20ms | 22ms | 2ms | 9.81
| PostPersistentNotificationStore.Get | p99 | 21ms | 23ms | 2ms | 9.69
| ThreadStore.GetTeamsUnreadForUser | p99 | 21ms | 23ms | 2ms | 9.45
| PreferenceStore.GetAll | p99 | 21ms | 23ms | 2ms | 9.42
| ChannelStore.GetMembersForUserWithPagination | p99 | 21ms | 23ms | 2ms | 9.37
| ProductNoticesStore.View | p99 | 146ms | 155ms | 9ms | 6.16
| ChannelStore.SaveMember | p99 | 95ms | 98ms | 3ms | 3.16
| UserStore.AutocompleteUsersInChannel | p99 | 169ms | 174ms | 5ms | 2.96
| UserStore.GetAllProfilesInChannel | p99 | 471ms | 477ms | 6ms | 1.27
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PropertyValueStore.SearchPropertyValues | avg | 2ms | 0s | -2ms | -117.43
| RetentionPolicyStore.GetCount | avg | 5ms | 0s | -5ms | -107.37
| RetentionPolicyStore.GetAll | avg | 56ms | 0s | -56ms | -100.39
| UserStore.GetProfilesInChannel | avg | 24ms | 0s | -24ms | -100.12
| ChannelStore.GetTeamChannels | avg | 21ms | 0s | -21ms | -99.90
| ChannelStore.CreateSidebarCategory | avg | 14ms | 0s | -14ms | -98.48
| ThreadStore.MarkAllAsReadByTeam | avg | 3ms | 0s | -3ms | -97.44
| ChannelBookmarkStore.UpdateSortOrder | avg | 7ms | 0s | -7ms | -96.36
| UserStore.GetProfileByGroupChannelIdsForUser | avg | 4ms | 0s | -4ms | -89.52
| ChannelStore.GetMembers | avg | 4ms | 2ms | -2ms | -53.39
| StatusStore.SaveOrUpdateMany | avg | 10ms | 5ms | -5ms | -51.95
| SessionStore.GetSessionsExpired | avg | 6ms | 4ms | -2ms | -34.10
| ChannelStore.AutocompleteInTeamForSearch | avg | 52ms | 36ms | -16ms | -30.95
| ChannelBookmarkStore.Save | avg | 12ms | 9ms | -3ms | -24.69
| PostStore.SearchPostsForUser | avg | 123ms | 96ms | -27ms | -21.89
| ChannelStore.GetSidebarCategory | avg | 9ms | 7ms | -2ms | -21.46
| ChannelStore.UpdateSidebarCategories | avg | 41ms | 33ms | -8ms | -19.67
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 14ms | 12ms | -2ms | -13.88
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 5ms | 0s | -5ms | -100.92
| ChannelStore.CreateSidebarCategory | p99 | 25ms | 0s | -25ms | -100.60
| RetentionPolicyStore.GetAll | p99 | 100ms | 0s | -100ms | -100.50
| ChannelBookmarkStore.UpdateSortOrder | p99 | 10ms | 0s | -10ms | -100.50
| PropertyValueStore.SearchPropertyValues | p99 | 5ms | 0s | -5ms | -100.50
| UserStore.GetProfilesInChannel | p99 | 239ms | 0s | -239ms | -99.79
| ChannelStore.GetTeamChannels | p99 | 48ms | 0s | -48ms | -98.97
| ChannelStore.AutocompleteInTeamForSearch | p99 | 755ms | 109ms | -646ms | -85.56
| UserStore.GetByUsername | p99 | 24ms | 5ms | -19ms | -78.84
| PostStore.GetPostIdAfterTime | p99 | 21ms | 5ms | -16ms | -76.92
| ThreadStore.Get | p99 | 19ms | 5ms | -14ms | -75.47
| PropertyFieldStore.SearchPropertyFields | p99 | 17ms | 5ms | -12ms | -71.68
| JobStore.UpdateOptimistically | p99 | 35ms | 10ms | -25ms | -70.92
| JobStore.GetCountByStatusAndType | p99 | 32ms | 9ms | -23ms | -70.77
| PropertyGroupStore.Get | p99 | 17ms | 5ms | -12ms | -69.16
| StatusStore.UpdateExpiredDNDStatuses | p99 | 12ms | 5ms | -7ms | -60.87
| ChannelStore.UpdateSidebarCategories | p99 | 224ms | 91ms | -133ms | -59.24
| SessionStore.GetSessionsExpired | p99 | 24ms | 10ms | -14ms | -58.46
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 22ms | 9ms | -13ms | -57.91
| PostStore.SetPostReminder | p99 | 23ms | 10ms | -13ms | -56.03
| JobStore.GetAllByTypePage | p99 | 10ms | 5ms | -5ms | -52.08
| StatusStore.SaveOrUpdate | p99 | 25ms | 12ms | -13ms | -52.05
| TemporaryPostStore.GetExpiredPosts | p99 | 10ms | 5ms | -5ms | -51.81
| PostStore.GetPostReminderMetadata | p99 | 21ms | 10ms | -11ms | -51.68
| UserStore.GetProfilesNotInChannel | p99 | 10ms | 5ms | -5ms | -51.53
| ChannelStore.GetSidebarCategory | p99 | 47ms | 25ms | -22ms | -46.48
| JobStore.Save | p99 | 9ms | 5ms | -4ms | -42.90
| PreferenceStore.DeleteCategoryAndName | p99 | 9ms | 5ms | -4ms | -42.33
| FileInfoStore.SetContent | p99 | 33ms | 22ms | -11ms | -32.96
| ChannelStore.GetFileCount | p99 | 11ms | 8ms | -3ms | -28.35
| ThreadStore.MarkAsRead | p99 | 8ms | 6ms | -2ms | -24.95
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 83ms | 68ms | -15ms | -18.17
| ChannelStore.Save | p99 | 43ms | 36ms | -7ms | -16.18
| ChannelStore.Autocomplete | p99 | 340ms | 300ms | -40ms | -11.76
| ChannelStore.GetByName | p99 | 28ms | 25ms | -3ms | -10.62
| PostStore.SearchPostsForUser | p99 | 969ms | 958ms | -11ms | -1.14
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| handleCheckCWSConnection | avg | 35ms | 50ms | 15ms | 42.43
| removeUserCustomStatus | avg | 94ms | 110ms | 16ms | 16.96
| addChannelMember | avg | 162ms | 175ms | 13ms | 8.03
| addTeamMember | avg | 580ms | 609ms | 29ms | 5.00
| login | avg | 82ms | 85ms | 3ms | 3.64
| createGroupChannel | avg | 242ms | 250ms | 8ms | 3.31
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| root | p99 | 5ms | 22ms | 17ms | 343.43
| getChannel | p99 | 10ms | 35ms | 25ms | 250.27
| createSchedulePost | p99 | 9ms | 21ms | 12ms | 128.02
| handleCheckCWSConnection | p99 | 50ms | 99ms | 49ms | 98.49
| getChannelUnread | p99 | 5ms | 9ms | 4ms | 80.78
| getChannelMembersForTeamForUser | p99 | 10ms | 13ms | 3ms | 30.83
| getDrafts | p99 | 7ms | 9ms | 2ms | 29.03
| createPost | p99 | 498ms | 595ms | 97ms | 19.49
| getChannelsForTeamForUser | p99 | 11ms | 13ms | 2ms | 18.34
| getTeamsUnreadForUser | p99 | 31ms | 36ms | 5ms | 16.02
| viewChannel | p99 | 32ms | 37ms | 5ms | 15.47
| getTeamMembersForUser | p99 | 21ms | 23ms | 2ms | 9.69
| getTeamScheduledPosts | p99 | 31ms | 34ms | 3ms | 9.66
| getCategoriesForTeamForUser | p99 | 34ms | 37ms | 3ms | 8.92
| getUsers | p99 | 23ms | 25ms | 2ms | 8.67
| getUser | p99 | 24ms | 26ms | 2ms | 8.48
| getChannelMember | p99 | 40ms | 43ms | 3ms | 7.51
| autocompleteUsers | p99 | 140ms | 148ms | 8ms | 5.73
| getPostsForChannel | p99 | 185ms | 195ms | 10ms | 5.40
| getClientConfig | p99 | 41ms | 43ms | 2ms | 4.86
| addTeamMember | p99 | 2.098s | 2.175s | 77ms | 3.67
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getProductNotices | avg | 2ms | 0s | -2ms | -125.38
| getUsersByGroupChannelIds | avg | 5ms | 0s | -5ms | -105.84
| updateChannelBookmarkSortOrder | avg | 12ms | 0s | -12ms | -103.38
| getConfig | avg | 14ms | 0s | -14ms | -100.27
| createChannel | avg | 170ms | 0s | -170ms | -100.13
| createCategoryForTeamForUser | avg | 16ms | 0s | -16ms | -97.90
| updateReadStateAllThreadsByUser | avg | 3ms | 0s | -3ms | -95.09
| listCPAFields | avg | 4ms | 0s | -4ms | -92.65
| listCPAValues | avg | 3ms | 0s | -3ms | -86.49
| getChannelMembers | avg | 5ms | 2ms | -3ms | -66.65
| followThreadByUser | avg | 20ms | 11ms | -9ms | -45.98
| createChannelBookmark | avg | 24ms | 14ms | -10ms | -41.14
| autocompleteChannelsForTeamForSearch | avg | 52ms | 36ms | -16ms | -30.91
| setPostReminder | avg | 34ms | 26ms | -8ms | -23.28
| searchPostsInTeam | avg | 132ms | 103ms | -29ms | -21.94
| updateCategoriesForTeamForUser | avg | 62ms | 49ms | -13ms | -20.85
| deletePost | avg | 20ms | 17ms | -3ms | -15.13
| getProfileImage | avg | 92ms | 85ms | -7ms | -7.64
| createDirectChannel | avg | 167ms | 163ms | -4ms | -2.40
| createUser | avg | 185ms | 181ms | -4ms | -2.16
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| listCPAValues | p99 | 10ms | 0s | -10ms | -104.57
| getGroups | p99 | 5ms | 0s | -5ms | -101.01
| getProductNotices | p99 | 5ms | 0s | -5ms | -101.01
| updateReadStateAllThreadsByUser | p99 | 5ms | 0s | -5ms | -101.01
| getUsersByGroupChannelIds | p99 | 5ms | 0s | -5ms | -100.92
| createCategoryForTeamForUser | p99 | 25ms | 0s | -25ms | -100.60
| updateChannelBookmarkSortOrder | p99 | 25ms | 0s | -25ms | -100.60
| getConfig | p99 | 25ms | 0s | -25ms | -100.60
| createChannel | p99 | 249ms | 0s | -249ms | -100.20
| listCPAFields | p99 | 27ms | 0s | -27ms | -99.55
| followThreadByUser | p99 | 230ms | 25ms | -205ms | -88.94
| autocompleteChannelsForTeamForSearch | p99 | 755ms | 109ms | -646ms | -85.56
| setPostReminder | p99 | 232ms | 50ms | -182ms | -78.45
| updateCategoriesForTeamForUser | p99 | 237ms | 99ms | -138ms | -58.17
| deletePost | p99 | 49ms | 25ms | -24ms | -49.36
| createChannelBookmark | p99 | 49ms | 25ms | -24ms | -49.23
| getJobsByType | p99 | 9ms | 5ms | -4ms | -45.71
| searchAllChannels | p99 | 340ms | 300ms | -40ms | -11.76
| searchPostsInTeam | p99 | 975ms | 958ms | -17ms | -1.74
| getProfileImage | p99 | 397ms | 392ms | -5ms | -1.26
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.688
| BotStore.Get |  Avg| 2ms| 3ms | 1ms | 44.722
| |  P99| 5ms| 9ms | 4ms | 80.808
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 12ms| 9ms | -3ms | -24.687
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 7ms| 0s | -7ms | -96.363
| |  P99| 10ms| 0s | -10ms | -100.503
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 4ms | 1ms | 28.589
| |  P99| 17ms| 19ms | 2ms | 11.508
| ChannelStore.AnalyticsCountAll |  Avg| 19ms| 21ms | 2ms | 10.416
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 39ms| 38ms | -1ms | -2.559
| |  P99| 340ms| 300ms | -40ms | -11.759
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 52ms| 36ms | -16ms | -30.950
| |  P99| 755ms| 109ms | -646ms | -85.563
| ChannelStore.CreateDirectChannel |  Avg| 20ms| 21ms | 1ms | 5.072
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.CreateInitialSidebarCategories |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 52ms| 64ms | 12ms | 23.254
| ChannelStore.CreateSidebarCategory |  Avg| 14ms| 0s | -14ms | -98.481
| |  P99| 25ms| 0s | -25ms | -100.604
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 17ms | 2ms | 13.644
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.221
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 14ms| 12ms | -2ms | -13.877
| |  P99| 83ms| 68ms | -15ms | -18.175
| ChannelStore.GetBoardChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 28ms| 25ms | -3ms | -10.616
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 13ms | 3ms | 28.926
| ChannelStore.GetChannelsByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.055
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 8ms | -3ms | -28.349
| ChannelStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.406
| ChannelStore.GetMany |  Avg| 2ms| 3ms | 1ms | 53.331
| |  P99| 5ms| 23ms | 18ms | 363.636
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.103
| ChannelStore.GetMemberCount |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 45ms| 45ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 40ms| 41ms | 1ms | 2.474
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 4ms| 2ms | -2ms | -53.386
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 13ms | 3ms | 31.161
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 3ms| 4ms | 1ms | 34.111
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 23ms | 2ms | 9.367
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 30ms| 33ms | 3ms | 9.981
| ChannelStore.GetSidebarCategory |  Avg| 9ms| 7ms | -2ms | -21.465
| |  P99| 47ms| 25ms | -22ms | -46.479
| ChannelStore.GetTeamChannels |  Avg| 21ms| 0s | -21ms | -99.897
| |  P99| 48ms| 0s | -48ms | -98.969
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 16ms | 3ms | 22.571
| ChannelStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 43ms| 36ms | -7ms | -16.185
| ChannelStore.SaveMember |  Avg| 27ms| 28ms | 1ms | 3.663
| |  P99| 95ms| 98ms | 3ms | 3.160
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 18ms | 2ms | 12.426
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.687
| ChannelStore.UpdateSidebarCategories |  Avg| 41ms| 33ms | -8ms | -19.669
| |  P99| 224ms| 91ms | -133ms | -59.243
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 2ms | 1ms | 70.736
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 18ms | 9ms | 103.846
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 4ms| 79ms | 75ms | 1805.145
| |  P99| 5ms| 248ms | 243ms | 4901.460
| DraftStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 28.223
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 3ms| 4ms | 1ms | 29.419
| |  P99| 10ms| 10ms | 0s | 0.000
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.114
| DraftStore.Upsert |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.353
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.487
| EmojiStore.GetMultipleByName |  Avg| 1ms| 2ms | 1ms | 67.254
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 15ms | 5ms | 50.010
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.033
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| FileInfoStore.SetContent |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 33ms| 22ms | -11ms | -32.959
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 19ms | 2ms | 12.043
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.063
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 15ms | 2ms | 15.173
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 2ms | 1ms | 68.717
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.484
| JobStore.GetAllByTypePage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -52.083
| JobStore.GetCountByStatusAndType |  Avg| 3ms| 2ms | -1ms | -36.439
| |  P99| 32ms| 9ms | -23ms | -70.769
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 4ms| 3ms | -1ms | -26.556
| |  P99| 9ms| 5ms | -4ms | -42.895
| JobStore.UpdateOptimistically |  Avg| 4ms| 3ms | -1ms | -25.505
| |  P99| 35ms| 10ms | -25ms | -70.922
| JobStore.UpdateStatus |  Avg| 5ms| 4ms | -1ms | -19.672
| |  P99| 17ms| 17ms | 0s | 0.000
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 4ms| 5ms | 1ms | 28.040
| |  P99| 9ms| 40ms | 31ms | 340.659
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 3ms | 1ms | 52.571
| |  P99| 9ms| 21ms | 12ms | 140.351
| PostPersistentNotificationStore.Get |  Avg| 4ms| 3ms | -1ms | -26.053
| |  P99| 21ms| 23ms | 2ms | 9.685
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPostWithContext |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.418
| PostStore.AnalyticsPostCount |  Avg| 3ms| 254ms | 251ms | 8728.437
| |  P99| 5ms| 495ms | 490ms | 9895.007
| PostStore.AnalyticsPostCountByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Delete |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.424
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 15ms | 2ms | 15.605
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 5ms | -16ms | -76.923
| PostStore.GetPostReminderMetadata |  Avg| 6ms| 5ms | -1ms | -17.124
| |  P99| 21ms| 10ms | -11ms | -51.680
| PostStore.GetPostReminders |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 4ms| 3ms | -1ms | -28.316
| |  P99| 22ms| 21ms | -1ms | -4.512
| PostStore.GetPostsAfter |  Avg| 3ms| 2ms | -1ms | -37.836
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 42ms| 42ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetVisiblePostIdAroundTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.854
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 44ms| 45ms | 1ms | 2.288
| PostStore.SearchPostsForUser |  Avg| 123ms| 96ms | -27ms | -21.894
| |  P99| 969ms| 958ms | -11ms | -1.136
| PostStore.SetPostReminder |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 23ms| 10ms | -13ms | -56.035
| PostStore.Update |  Avg| 12ms| 13ms | 1ms | 8.082
| |  P99| 25ms| 25ms | 0s | 0.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -42.328
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 23ms | 2ms | 9.417
| PreferenceStore.Save |  Avg| 9ms| 10ms | 1ms | 10.729
| |  P99| 47ms| 48ms | 1ms | 2.117
| ProductNoticesStore.GetViews |  Avg| 1ms| 2ms | 1ms | 84.316
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 34ms| 35ms | 1ms | 2.952
| |  P99| 146ms| 155ms | 9ms | 6.159
| PropertyFieldStore.SearchPropertyFields |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 5ms | -12ms | -71.678
| PropertyGroupStore.Get |  Avg| 2ms| 1ms | -1ms | -51.005
| |  P99| 17ms| 5ms | -12ms | -69.163
| PropertyValueStore.SearchPropertyValues |  Avg| 2ms| 0s | -2ms | -117.433
| |  P99| 5ms| 0s | -5ms | -100.501
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| RetentionPolicyStore.GetAll |  Avg| 56ms| 0s | -56ms | -100.391
| |  P99| 100ms| 0s | -100ms | -100.503
| RetentionPolicyStore.GetCount |  Avg| 5ms| 0s | -5ms | -107.375
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 21ms | 16ms | 323.170
| ScheduledPostStore.CreateScheduledPost |  Avg| 3ms| 4ms | 1ms | 30.828
| |  P99| 5ms| 21ms | 16ms | 323.232
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 3ms| 2ms | -1ms | -39.098
| |  P99| 22ms| 9ms | -13ms | -57.906
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.368
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 37ms| 38ms | 1ms | 2.687
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -5.121
| SessionStore.GetSessionsExpired |  Avg| 6ms| 4ms | -2ms | -34.099
| |  P99| 24ms| 10ms | -14ms | -58.455
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 31ms| 32ms | 1ms | 3.261
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 18ms | 3ms | 19.905
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 4ms| 3ms | -1ms | -23.837
| |  P99| 25ms| 12ms | -13ms | -52.054
| StatusStore.SaveOrUpdateMany |  Avg| 10ms| 5ms | -5ms | -51.953
| |  P99| 43ms| 44ms | 1ms | 2.336
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 5ms | -7ms | -60.870
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.191
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.637
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.413
| TeamStore.GetActiveMemberCount |  Avg| 34ms| 33ms | -1ms | -2.943
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.026
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.104
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 19ms | 3ms | 18.832
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 3ms | 1ms | 40.844
| |  P99| 21ms| 22ms | 1ms | 4.758
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.311
| TeamStore.GetTotalMemberCount |  Avg| 34ms| 33ms | -1ms | -2.980
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 64ms| 75ms | 11ms | 17.218
| TemporaryPostStore.GetExpiredPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -51.813
| ThreadStore.Get |  Avg| 2ms| 1ms | -1ms | -52.660
| |  P99| 19ms| 5ms | -14ms | -75.473
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 33.263
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 23ms | 2ms | 9.453
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 13.267
| ThreadStore.GetThreadForUser |  Avg| 4ms| 5ms | 1ms | 22.497
| |  P99| 20ms| 21ms | 1ms | 4.967
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 4ms| 5ms | 1ms | 22.541
| |  P99| 21ms| 22ms | 1ms | 4.754
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 10.876
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.935
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 10.919
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.357
| ThreadStore.MaintainMembership |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.842
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 0s | -3ms | -97.438
| |  P99| 5ms| 0s | -5ms | -101.010
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -24.948
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 3ms | 1ms | 60.635
| |  P99| 5ms| 10ms | 5ms | 100.980
| UserStore.AnalyticsActiveCount |  Avg| 13ms| 12ms | -1ms | -7.769
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 1ms | -1ms | -60.753
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 169ms| 174ms | 5ms | 2.960
| UserStore.Count |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 43ms| 44ms | 1ms | 2.320
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 13ms | 3ms | 30.042
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 19ms | 2ms | 11.755
| UserStore.GetAllProfilesInChannel |  Avg| 149ms| 155ms | 6ms | 4.030
| |  P99| 471ms| 477ms | 6ms | 1.273
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 5ms | -19ms | -78.839
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.595
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 4ms| 0s | -4ms | -89.516
| |  P99| 5ms| 0s | -5ms | -100.918
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 17ms | 3ms | 21.756
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 24ms| 0s | -24ms | -100.124
| |  P99| 239ms| 0s | -239ms | -99.791
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -51.532
| UserStore.GetUnreadCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.927
| UserStore.Save |  Avg| 119ms| 124ms | 5ms | 4.219
| |  P99| 248ms| 249ms | 1ms | 0.403
| UserStore.Search |  Avg| 29ms| 29ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| UserStore.TryIncrementFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.389
| UserStore.Update |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 20ms| 23ms | 3ms | 14.688
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.287
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 20ms| 22ms | 2ms | 10.027
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 20ms| 22ms | 2ms | 9.813
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.401
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 11.105
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 162ms| 175ms | 13ms | 8.028
| | P99| 250ms| 250ms | 0s | 0.000
| addTeamMember | Avg| 580ms| 609ms | 29ms | 4.999
| | P99| 2.098s| 2.175s | 77ms | 3.670
| autocompleteChannelsForTeamForSearch | Avg| 52ms| 36ms | -16ms | -30.909
| | P99| 755ms| 109ms | -646ms | -85.563
| autocompleteUsers | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 140ms| 148ms | 8ms | 5.725
| createCategoryForTeamForUser | Avg| 16ms| 0s | -16ms | -97.900
| | P99| 25ms| 0s | -25ms | -100.604
| createChannel | Avg| 170ms| 0s | -170ms | -100.126
| | P99| 249ms| 0s | -249ms | -100.201
| createChannelBookmark | Avg| 24ms| 14ms | -10ms | -41.143
| | P99| 49ms| 25ms | -24ms | -49.231
| createDirectChannel | Avg| 167ms| 163ms | -4ms | -2.396
| | P99| 248ms| 248ms | 0s | 0.000
| createGroupChannel | Avg| 242ms| 250ms | 8ms | 3.312
| | P99| 496ms| 495ms | -1ms | -0.202
| createPost | Avg| 135ms| 135ms | 0s | 0.000
| | P99| 498ms| 595ms | 97ms | 19.493
| createSchedulePost | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 9ms| 21ms | 12ms | 128.024
| createUser | Avg| 185ms| 181ms | -4ms | -2.157
| | P99| 474ms| 471ms | -3ms | -0.633
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| deletePost | Avg| 20ms| 17ms | -3ms | -15.125
| | P99| 49ms| 25ms | -24ms | -49.357
| followThreadByUser | Avg| 20ms| 11ms | -9ms | -45.983
| | P99| 230ms| 25ms | -205ms | -88.937
| getAgents | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getAgentsStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 23ms | 1ms | 4.589
| getCategoriesForTeamForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 34ms| 37ms | 3ms | 8.920
| getChannel | Avg| 4ms| 5ms | 1ms | 22.868
| | P99| 10ms| 35ms | 25ms | 250.270
| getChannelMember | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 40ms| 43ms | 3ms | 7.511
| getChannelMembers | Avg| 5ms| 2ms | -3ms | -66.650
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 13ms | 3ms | 30.835
| getChannelMembersForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 22ms| 23ms | 1ms | 4.644
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 9ms | 4ms | 80.783
| getChannelsForTeamForUser | Avg| 2ms| 3ms | 1ms | 40.319
| | P99| 11ms| 13ms | 2ms | 18.337
| getChannelsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 21ms | 1ms | 4.972
| getClientConfig | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 41ms| 43ms | 2ms | 4.861
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getConfig | Avg| 14ms| 0s | -14ms | -100.265
| | P99| 25ms| 0s | -25ms | -100.604
| getDrafts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 9ms | 2ms | 29.032
| getFilePreview | Avg| 40ms| 40ms | 0s | 0.000
| | P99| 94ms| 95ms | 1ms | 1.060
| getFileThumbnail | Avg| 39ms| 39ms | 0s | 0.000
| | P99| 92ms| 91ms | -1ms | -1.085
| getFilteredUsersStats | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getGroups | Avg| 1ms| 0s | -1ms | -69.911
| | P99| 5ms| 0s | -5ms | -101.010
| getJobsByType | Avg| 1ms| 2ms | 1ms | 114.614
| | P99| 9ms| 5ms | -4ms | -45.713
| getPostThread | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getPostsForChannel | Avg| 21ms| 22ms | 1ms | 4.875
| | P99| 185ms| 195ms | 10ms | 5.397
| getPostsForChannelAroundLastUnread | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 83ms| 82ms | -1ms | -1.203
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 23ms | 1ms | 4.626
| getPrevTrialLicense | Avg| 1ms| 2ms | 1ms | 70.245
| | P99| 5ms| 5ms | 0s | 0.000
| getProductNotices | Avg| 2ms| 0s | -2ms | -125.379
| | P99| 5ms| 0s | -5ms | -101.010
| getProfileImage | Avg| 92ms| 85ms | -7ms | -7.644
| | P99| 397ms| 392ms | -5ms | -1.260
| getPropertyFields | Avg| 3ms| 4ms | 1ms | 32.479
| | P99| 5ms| 5ms | 0s | 0.000
| getPublicChannelsForTeam | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getRolesByNames | Avg| 1ms| 2ms | 1ms | 97.685
| | P99| 5ms| 5ms | 0s | 0.000
| getServerLimits | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 24ms| 25ms | 1ms | 4.098
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 23ms | 2ms | 9.689
| getTeamScheduledPosts | Avg| 4ms| 5ms | 1ms | 22.548
| | P99| 31ms| 34ms | 3ms | 9.655
| getTeamStats | Avg| 34ms| 33ms | -1ms | -2.928
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 22ms | 1ms | 4.736
| getTeamsUnreadForUser | Avg| 4ms| 5ms | 1ms | 22.577
| | P99| 31ms| 36ms | 5ms | 16.015
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 21ms | 1ms | 4.933
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 26ms | 2ms | 8.479
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 25ms | 2ms | 8.673
| getUsersByGroupChannelIds | Avg| 5ms| 0s | -5ms | -105.838
| | P99| 5ms| 0s | -5ms | -100.918
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 7ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 35ms| 50ms | 15ms | 42.426
| | P99| 50ms| 99ms | 49ms | 98.492
| listCPAFields | Avg| 4ms| 0s | -4ms | -92.646
| | P99| 27ms| 0s | -27ms | -99.547
| listCPAValues | Avg| 3ms| 0s | -3ms | -86.485
| | P99| 10ms| 0s | -10ms | -104.569
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| login | Avg| 82ms| 85ms | 3ms | 3.638
| | P99| 312ms| 315ms | 3ms | 0.962
| logout | Avg| 22ms| 22ms | 0s | 0.000
| | P99| 47ms| 48ms | 1ms | 2.128
| patchPost | Avg| 25ms| 26ms | 1ms | 3.972
| | P99| 50ms| 50ms | 0s | 0.000
| removeUserCustomStatus | Avg| 94ms| 110ms | 16ms | 16.964
| | P99| 247ms| 248ms | 1ms | 0.405
| root | Avg| 1ms| 2ms | 1ms | 98.441
| | P99| 5ms| 22ms | 17ms | 343.434
| saveReaction | Avg| 26ms| 26ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| searchAllChannels | Avg| 39ms| 38ms | -1ms | -2.546
| | P99| 340ms| 300ms | -40ms | -11.759
| searchGroupChannels | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 17ms| 18ms | 1ms | 5.902
| searchPostsInTeam | Avg| 132ms| 103ms | -29ms | -21.942
| | P99| 975ms| 958ms | -17ms | -1.744
| searchUsers | Avg| 30ms| 30ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| setPostReminder | Avg| 34ms| 26ms | -8ms | -23.280
| | P99| 232ms| 50ms | -182ms | -78.448
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 62ms| 49ms | -13ms | -20.853
| | P99| 237ms| 99ms | -138ms | -58.167
| updateChannelBookmarkSortOrder | Avg| 12ms| 0s | -12ms | -103.381
| | P99| 25ms| 0s | -25ms | -100.604
| updatePreferences | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 20ms| 19ms | -1ms | -4.879
| updateReadStateAllThreadsByUser | Avg| 3ms| 0s | -3ms | -95.090
| | P99| 5ms| 0s | -5ms | -101.010
| updateReadStateThreadByUser | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 60ms| 60ms | 0s | 0.000
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 437ms| 441ms | 4ms | 0.916
| | P99| 991ms| 992ms | 1ms | 0.101
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 13ms| 13ms | 0s | 0.000
| viewChannel | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 32ms| 37ms | 5ms | 15.471
